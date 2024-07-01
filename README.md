# GitHub Fundamentals
<ul>
    <li><a href="#git-and-github">Git and GitHub</a>
        <ul>
            <li><a href="#git">Git</a></li>
            <li><a href="#github">GitHub</a></li>
        </ul>
    </li>
    <li><a href="#common-terms">Common terms</a></li>
    <li><a href="#installing-git">Installing git</a>
        <ul>
            <li><a href="#windows">Windows</a></li>
            <li><a href="#linux">Linux</a></li>
        </ul>
    </li>
    <li><a href="#installing-git-in-local-repository">Installing Git in local repository</a>
        <ul>
            <li><a href="#install-git">Install git</a></li>
            <li><a href="#open-terminal-or-command-prompt">Open terminal or command prompt</a></li>
        </ul>
    </li>
    <li><a href="#update-changes">Update changes</a>
        <ul>
            <li><a href="#git-add">git add</a></li>
            <li><a href="#to-add-all-changes">To add all changes</a></li>
            <li><a href="#to-add-specific-file">To add specific file</a></li>
            <li><a href="#git-commit">git commit</a></li>
            <li><a href="#git-log">git log</a></li>
        </ul>
    </li>
    <li><a href="#branches">Branches</a>
        <ul>
            <li><a href="#to-provide-all-branch">To provide all branch</a></li>
            <li><a href="#create-new-branch">Create new branch</a></li>
            <li><a href="#delete-a-branch">Delete a branch</a></li>
        </ul>
    </li>
    <li><a href="#merge">Merge</a>
        <ul>
            <li><a href="#switch-to-the-target-branch">Switch to the Target Branch</a></li>
        </ul>
    </li>
    <li><a href="#pullrequest">Pull request</a></li>
    <li><a href="#clone">Clone</a>
        <ul>
            <li><a href="#https">HTTPS</a></li>
            <li><a href="#ssh">SSH</a></li>
            <li><a href="#github-cli">GitHub CLI</a>
                <ul>
                    <li><a href="#core-commands">Core commands</a></li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#Readme-file">Readme file</a></li>
    <li><a href="#gitignore-file">.gitignore file</a></li>
    <li><a href="#license-file">License file</a></li>
    <li><a href="#github-codespace">GitHub codespace</a></li>
</ul>


# Git and GitHub
## Git 
>Git is a distributed version control system (DVCS) designed to track changes in source code during software development.
## GitHub
>GitHub, on the other hand, is a web-based platform built around Git that provides hosting for Git repositories.
## Common terms :
>Clone: Cloning a repository means creating a local copy on your machine from a remote repository hosted on GitHub.

>Branch:A branch is a parallel version of the repository that allows developers to work on different features or fixes independently without affecting the main codebase

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
## Installing Git in local repository
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
We can do cloning in three ways 1.HTTPS  2.SSH  3.GitHubCLI
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
<li>gh auth</li>
<li>gh issue</li>
<li>gh codespace</li>
<li>gh browse</li>

## Readme file
```
The README file serves as documentation to provide essential information about your project to anyone visiting your repository.
```
## .gitignore file
```
The .gitignore file is a text file used by Git to specify files and directories that should be ignored and not tracked by version control.
```
## Licence file
```
A license file in a software project is a legal document that specifies the terms under which the software can be used, modified, and distributed.
```
## GitHub Codespace
```
GitHub Codespaces is a cloud-based development environment that allows you to develop and test your code directly within your GitHub repository. It provides a fully-configured development environment in the cloud, accessible from your browser or Visual Studio Code, eliminating the need for setting up and maintaining local development environments.
```
