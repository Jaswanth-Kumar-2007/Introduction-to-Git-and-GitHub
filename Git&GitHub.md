# Git and GitHub

## What is Git

Git - Version Control System is a tool that helps to track changes in code

Git is a Version Control System 

## Why Git

It is Popular

It is Free & Open Source

It is Fast and Scalable

### Official Website for [Git](https://git-scm.com/)

## What Git Does

Tracks the History of Code

Helps to Collaborate with Teams and Others

## What is Github 

GitHub - Website that allows developers to store and manage their code using Git.

### Official Website for [GitHub](https://github.com/)

---> README.md -> md means Mark Down

## Setting Up Git 

Visual Studio Code

Windows(Git Bash)

Mac(Terminal)

### Configuring Git 

```git
git config --global user.name "My Username"

git config --global user.email "My Email-ID"

git config --list
```

## Clone and Status

**Clone - Cloning a Repository on our Local Machine
         
         (git clone <-some link->)

**Status - Display the State of the Code

         (git status)

---> cd - Change Directory 

---> M - Modified

### Types of Git Status

```git
**untracked -> new files that git doesnt yet track

**modified -> changed

**staged -> file is ready to be commited

**unmodified -> unchanged
```

## Add & Commit

**add - adds new or changed files in your working directory to the Git staging Area

      (git add <-file name->)

**commit - it is the record of the message

     (git commit -m "some message")

--->git add . -> covers all files 

## Push Command 

**push - upload local repo content to remote repo

    (git push origin main)

---> git push origin main -> origin means local file name , main means the branch in github repository 

## Init Command

**init - used to create a new git repo

---> git init
---> git remote add origin <-link->
---> git remote -v            (to verify Remote)
---> git branch               (to check branch)
---> git branch -M main       (to rename branch)
---> git push origin main

--->mkdir -> Make a New Directory

--->U -> Untracked

```git
--->Ex : 
    ->Create a Folder
    ->git init
    ->git status
    ->git add .
    ->git commit -m "Add Initial Files"(Something Text)
    """
      Create a Repository at GitHub
    """
    ->git remote add origin <-Github Link->
    ->git remote -v
    ->git branch                 (default Max - Master will be)
    ->git branch -M main
    ->git push -u orgin main
        ---> u means upstream
```

# WorkFlow

--->Local Git

**GitHub Repo -> Clone -> Changes -> Add -> Commit -> Push

# Branch Commands

--->git branch                           (to check branch)

--->git branch -M main                   (to rename branch) 

--->git checkout <-branch name->         (to navigate)

--->git checkout -b <-new branch-name->  (to create new branch)

--->git branch -d <-branch name->        (to delete branch)

# Merging Codes

**Way 1

---> git diff <-branch name->        (to compare commits,branches,files & more)

--->git merge <-branch name->        (to merge 2 branches)

**Way 2

--->Create a PR

# Pull Request 

  (It Tells You Tell Others about Changes you've pushed to a branch in a repository on GitHub)

# Pull Command

   (git pull origin main)

   (Used to fetch and download content from a remote repo and immediately update the local repo to match the count)

# Resolving Merge Conflicts 

   (An Event that takes place where Git is unable to automatically resolve differences in code between two commits)

# Undoing Changes

---> Case 1 : Staged Changes

     -> git reset <-file name->
     -> git reset

---> Case 2 : commited changes (for one commit)

     -> git reset HEAD~1

---> Case 3 : commited changes (for many commits)

     -> git reset <-commit hash->
     -> git reset --hard<-commit hash->

--->git log -> to check the commits hisotry

# Fork

    (Afork is a new repository that shares code and visibility settings with the original "upstream" repository)

    (Fork is a rough copy)



         
