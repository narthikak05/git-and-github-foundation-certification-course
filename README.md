# Git and GitHub
## Git 
>Git is a distributed version control system (DVCS) designed to track changes in source code during software development.
## GitHub
>GitHub, on the other hand, is a web-based platform built around Git that provides hosting for Git repositories.
### Common terms :
>clone: Cloning a repository means creating a local copy on your machine from a remote repository hosted on GitHub.

>branch:A branch is a parallel version of the repository that allows developers to work on different features or fixes independently without affecting the main codebase

>Commit: A commit represents a snapshot of changes made to the repository at a specific time. 

>Fork: Forking a repository means creating a personal copy of someone else's repository. This copy is independent and allows you to make changes without affecting the original repository.

>Merge: Merging combines changes from one branch (source branch) into another (target branch), typically after reviewing and approving changes via a pull request.
## Installing git
### Windows:
```
https://git-scm.com
```
### Linux:
```
https://git-scm.com/download/linux
```
## Git in local repository
### Install git
Install git from official website:https://git-scm.com
### Open terminal or command propmt
### Initalize new git repository
git init

## Update changes
## git add
It is used to add changes.
### To add all changes
```
git add .
```
### To add specific file
```
git add filename
```
## git commit
It is used to record changes to the repository. It captures a snapshot of the changes that have been staged using git add and creates a permanent record of those changes in the repository's history.
### To commit changes
```
git commit -m "Your commit message"
```

## git log
 It is a command used to display a history of commits in a repository.
 ### To view simple list of commit
 ```
git log
```
## Branches
### To provide all branch
```
git branch
```
### Create new branch
```
set  branch branch_name
```
### Delete a branch
```
git branch -d branch-name
```
## Merge
Merging refers to combining changes from one branch into another branch.
### Switch to the Target Branch
```
git checkout main
```
## Pullrequest
A pull request in Git is a request to merge changes from a feature branch into the main branch. It facilitates code review and collaboration among team members before changes are merged.

## Clone
We can do cloning in three ways **1.HTTPS    2.SSH    3.GitHubCLI**
### HTTPS
It provides a secure means of communication between your local machine and GitHub servers.
```
git clone https://github.com/Github-narthika/git-and-github-foundation-certification-course.git
```
### SSH
SSH (Secure Shell) is a cryptographic network protocol used for secure communication between computers.
```
git@github.com:Github-narthika/git-and-github-foundation-certification-course.git
```
### GitHubCLI
It is a command line interface to interact with github account.
### core commands
-gh auth
-gh browse
-gh issue
-gh codespace
