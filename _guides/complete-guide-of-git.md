---
title: "Complete guide of git"
authors: ismaelc
date: 2023-10-12
description: "Learn deeply about git."
---

## About git

git is a **version control system**. A version control system is a software that allows to store different versions of applications and/or files at the same time, with the same files. With git it's possible to change versions by simply using the command checkout. It has been designed for versioning code, no for versioning documents, and essentially it allows to version code very good. In fact, it's usually considered the better version control system, and inside Scifir you're suggested to use it in all your software projects. git is not good for versioning documents, for that purpose you should store in the same file both texts, or just have two different files. You can try to use git for documents, but you shouldn't get good results at all, cause git is not comfortable for that purpose.

git has been created by **Linus Torvalds**, the **founder of Linux**, in 19 october of 2007. Since then, it has become one of the most important tools for developing software of the world. It has **GPL license**, and then it's free to use by anyone.

### Alternatives to git

The alternatives to git are usually considered worst than git, but they are sometimes used and then their names should be known by every programmer. They are **hg**, **bazaar** and **svn**. In general, they are worst than git, because the code repository sizes more. hg is a **fork of git**, and it allows to be customized in great part, it can be a good replacement for git if a feature of it is needed, the other options aren't usually considered better.

### How git stores different versions

git stores the different versions of files by storing all its file content, instead of storing just the difference. The difference is computed when it's needed when running some commands.

## Using git

### Git repositories

Everytime you use git, you use it inside a **git repository**. A git repository is a folder containing all files and folders versioned by git. git versions automatically all files and folders of the git repository, unless you configure it explicitly to don't do it inside the file **.gitignore**. A folder is a git repository if it contains the hidden folder **.git** inside it. If that folder exists, then all files and folders of the parent folder of .git are all being versioned by git.

git repositories can be **local repositories** or **remote repositories**. A local repository is a repository inside the local computer you are using, and a remote repository is a repository stored in another computer, and accessed through a network connection. Usually, the network connection is a normal internet connection, and the repository can be accessed by using an ssh key as authentication mechanism.

To start a new repository, use the command **git init** inside the folder you want to version. To copy a remote repository in order to have it in your local computer, use the command **git clone <remote_repository_url>** inside the folder you want to store the project. Usually, you should store all projects you clone inside a projects folder which should be inside your home directory. You can browse software repositories inside **GitHub**, **GitLab**, **SourceForge**, among other websites. There also exists **Bitbucket** as a private alternative to those websites, which is used by private companies.

To manage remote repositories the command to use is **git remote**. When starting a new git repository with git init, there's no remote repository. To add one, use **git remote add <remote_name> <remote_url>**. You can list all remote repositories configured inside for your local git repository with the command **git remote**. When you use git clone, the remote repository that you have cloned will automatically be configured as a remote repository, it's not needed to configure it with git remote add. It's possible to have more than one remote repository, which makes sense for some purpose, like for example **security copies**.

### Branches and commits

git stores the different versions of files inside **commits**. The folders are stored or not based on the files they contain, they are not tracked separately from files. All commits contain a different version of the software project. When you do any change to any amount of files that you want to store permanently through git, then you have to do a new commit. When you do a commit, that commit is added next to the previous commit, and it automatically becomes the last commit.

## Summary of concepts

- **git repository:** A directory managed by git.
- **git server:** Server of a git repository, it allows to do git operations with the repository, as can be to clone it and to make code changes to it.
- **commit:**
- **branch:**
- **working tree:** A set of files and folders.

## Most important commands

- **git init:** Creates a new git repository inside the current directory of the command-line.
- **git clone:** Clones a remote repository.
- **git config:** It allows to add or change configuration variables of git, that are stored inside **.gitconfig**.
	- **git config -l:** Lists all configuration variables of the current repository.
	- **git config -e:** Opens an editor of the configuration file. It defaults to the file **.git/config** of the current repository, **--global** and **--system** can be used to open .gitconfig.
- **git status:** It gives information about all the files added for a commit and the current branch you're working on, and the ones that aren't in the head.
- **git remote:** Allows to configure remote repositories from which to push your changes, and to pull and fetch changes.
- **git fetch:** Loads a remote branch in your local repository.
- **git checkout:** Changes to the specified branch, or to the specified commit.
- **git branch:** It creates a new branch, starting from the current commit.
- **git add:** Add a file to the head.
- **git mv:** Renames a file. **Very important** command to use in replacement of the normal mv (mv of bash, not of git), because it allows git to track the file, using the normal mv command should be forbidden for files pertaining to a git repository.
- **git reset --hard HEAD:** It deletes the files added to the head. Useful if you've mistaked and you've added a file that doesn't has to be on the head.
- **git commit:** It makes a commit with the files in the head.
	- **--author=<author>:** Specifies a new author, which can be an email address or a pattern of an author of a previous commit.
- **git revert <hash_commit>:** Reverts the commit, specified by its hash.
- **git diff:** Show changes between commits, between a commit and the working tree, etc.
- **git merge:** Merges two different branches. When doing a merge, one of the two branches merged gets a new commit containing the result of the merge.
- **git push:** It uploads the commits on your local repository to a remote repository.
- **git pull:** Updates your current branch with changes in a remote repository. The updates are done through a merge.
- **git log:** Lists all the previous commits, in order.

### git remote

### git checkout -- and git reset

### File .gitignore

The file **.gitignore** of a git repository allows to specify files that are inside the git repository but that are not tracked by git and, then, that aren't listed by git status and that can't be added to the head with git add. A pattern can be specified by using the character * to mean any character.

### File .gitconfig

The file **.gitconfig** allows to configure git. Inside the repository, the file **.git/config** allows to override configuration options related to the global .gitconfig file. git can be configured with the file .gitconfig and with the command **git config**, the configuration options are the same. The most important configuration is the user and the email of the author of the commits, another important is the default text editor to use for merge messages.

## Other commands

- **git cherry-pick:** Checkouts to any previous commit.
- **git stash:** Discards your changes and stores them in the stash.
- **git submodule:** Manages git submodules, which are more git repositories inside the same git repository.
- **git tag:** Manages tag, which can be used to identify specific parts of the commit history. It's usually used to tag versions by version number.

## Software forges
