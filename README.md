# Starter Web Repo
-- first pound is the first level heading.
-- md format markdown format(for github uses.)
this is a simple website project for showing how to use git and github together.


## Introduction
this is for practice.

This repository is for showing how Git and GitHub work

## Purpose
provide example and some commands with their application.
Sample website with plenty of files for demos

## Deployment


## Sections to manag on git:
_______________________________    ________________________     ___________________________________
|                              |   |                       |   | Files in the reopsitory:          |
|files in the working director |-->|Staged Files: Comitted |-> | On github webpages - pushed files |
|   origin master              |   |_______________________|   |___________________________________|
|______________________________|

## Commands : 
git diff
--- takes no paramaters give the difference between what is staged and whats not.

git difftool
---- gives a visual representation of the staging area and the working directory. This commmand launches p4merge tool.
git difftool -- <Name of the file>
we can limit the tracking on a specific file on both diff and difftool.
git diff --staged HEAD
--- this command compares staged changes and what is in the repository.
git difftool --staged HEAD
--- gives the visual representation of the last commit in the branch with the last pushed to the repository.
** HEAD : Is the last in a list. in git, it is the refrence to the last change or commit.
-- so we can compare to refrences by git diff HEAD <ref>
or we can compare the last change with the one before it-- this is useful,,,,
git diff HEAD HEAD^
the '^' meand HEAD - 1
-- if the comparsion refrence is <null> it means that the file didnt exist before or in the last commit.



## HOW TO CONTRIBUTE
Please fork this repo and then issue Pull Request for review.


## Copyright notice



