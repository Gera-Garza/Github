# General info
This is the repository for the course of git/github with Platzi, here you will see what I consider to be the most used commands and some examples. But first what is git?.. **git** its a software for tracking changes in any set of files, usually used by programmers that are collaboring in develop source code, and Github its a provider of internet hosting for software development and version control using git.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Commands](#commands)
	
## Technologies
Project is created with:
* git bash
* github
	
## Setup
Download git from their page [git](https://git-scm.com/downloads)  and install it, and then register in [github](https://github.com/)

Then open git bash, left click in your folder and select git bash
## Commands
| Command       | Descripcion   | Example  |
| ------------- |:-------------:| -----:|
| `$ init`     | This command turns a directory into an empty Git repository  | `$ git init` |
| `$ add`     | Adds files in the to the staging area for Git|   `$ git add css` |
| `$ commit`| Record the changes made to the files to a local repository.| `$ git commit -m "Commit message in quotes"` |
| `$ status` | This command returns the current state of the repository    |   `$ cp image.png ~/images/test.png` |
| `$ config` |  git config is how to assign these settings. Two important settings are user user.name and user.email  |   `$ git config --global user.email "my@emailaddress.com"` |
| `$ branch` | To determine what branch the local repository is on, add a new branch, or delete a branch.| `$ git branch -a` |
| `$ checkout` | It is used for switching the branch where you are | `$  git checkout new_feature` |
| `$ merge` | Combines the changes from one branch to another branch  | `$ git merge new_feature` |
| `$clone` | To create a local working copy of an existing remote repository| `$ git clone https://github.com/Gera-Garza/Github.git ` |
| `$ pull`| This pulls the changes from the remote repository to the local computer | `$ git pull origin staging` |
| `$ push`   | Sends local commits to the remote repository   | `$ git push —all` |
| `$ stash` |Save changes made when they’re not in a state to commit them to a repository  | `$ git stash` |
| `$ stash pop` |Bring stashed work back to the working directory   |   `$git stash pop` |
| `$ log` |show the chronological commit history for a repository| `$git log` |
| `$ rm`     | Remove files or directories from the working index   | `$  git rm --cached css/style.css` |