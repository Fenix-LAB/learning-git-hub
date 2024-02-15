# This repository for leaning Git and GitHub
I am learning Git and GitHub, this repository contains the notes and commands that I have learned so far.

## Index
1. [What is Git?](#what-is-git)
2. [What is GitHub?](#what-is-github)
3. [What is a Repository?](#what-is-a-repository)
4. [What is a Branch?](#what-is-a-branch)
5. [What is a Commit?](#what-is-a-commit)
6. [What is a Pull Request?](#what-is-a-pull-request)
7. [What is a Merge Conflict?](#what-is-a-merge-conflict)
8. [What is a Fork?](#what-is-a-fork)
9. [What is a Clone?](#what-is-a-clone)
10. [How configure GitHub?](#how-configure-github)
11. [Git Commands](#git-commands)
12. [GitHub Commands](#github-commands)
13. [How create a new branch and switch to it?](#how-create-a-new-branch-and-switch-to-it)
14. [How to delete a branch?](#how-to-delete-a-branch)
15. [How to undo a commit?](#how-to-undo-a-commit)
16. [How move the changes from a branch to another?](#how-move-the-changes-from-a-branch-to-another)
17. [How to remove a commit that has been pushed to the remote repository?](#how-to-remove-a-commit-that-has-been-pushed-to-the-remote-repository)
18. [How to remove a commit that has not been pushed to the remote repository?](#how-to-remove-a-commit-that-has-not-been-pushed-to-the-remote-repository)
19. [How to remove a commit that has been pushed to the remote repository and you want to keep the changes?](#how-to-remove-a-commit-that-has-been-pushed-to-the-remote-repository-and-you-want-to-keep-the-changes)
20. [How to remove a commit that has been pushed to the remote repository and you want to discard the changes?](#how-to-remove-a-commit-that-has-been-pushed-to-the-remote-repository-and-you-want-to-discard-the-changes)
21. [How to remove a commit that has been pushed to the remote repository and you want to keep the changes in the staging area?](#how-to-remove-a-commit-that-has-been-pushed-to-the-remote-repository-and-you-want-to-keep-the-changes-in-the-staging-area)
22. [How to remove a commit that has been pushed to the remote repository and you want to keep the changes in the working directory?](#how-to-remove-a-commit-that-has-been-pushed-to-the-remote-repository-and-you-want-to-keep-the-changes-in-the-working-directory)
23. [How to remove a file from the staging area?](#how-to-remove-a-file-from-the-staging-area)
24. [How to remove a file from the working directory?](#how-to-remove-a-file-from-the-working-directory)
25. [How to rename a file?](#how-to-rename-a-file)
26. [How to show the changes between commits?](#how-to-show-the-changes-between-commits)
27. [How to show the changes between the working directory and the staging area?](#how-to-show-the-changes-between-the-working-directory-and-the-staging-area)
28. [How to show the changes between the working directory and the last commit?](#how-to-show-the-changes-between-the-working-directory-and-the-last-commit)
29. [How to show the changes between the staging area and the last commit?](#how-to-show-the-changes-between-the-staging-area-and-the-last-commit)
30. [How to show the changes between two branches?](#how-to-show-the-changes-between-two-branches)


## What is Git?
Git is a version control system that lets you manage and keep track of your source code history. It is designed to handle everything from small to very large projects with speed and efficiency.

## What is GitHub?
GitHub is a cloud-based platform that lets you store and manage your Git repositories. It has a web-based graphical interface and desktop as well as mobile integration. It also provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

## What is a Repository?
A repository is a directory or storage space where your projects can live. It can be a local repository stored on your computer and a remote repository stored on GitHub or any other online host.

## What is a Branch?
A branch is a parallel version of a repository. It is contained within the repository but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes.

## What is a Commit?
A commit, or "revision", is an individual change to a file (or set of files). It's like when you save a file, except with Git, every time you save it creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of what changes were made when and by who. Commits usually contain a commit message which is a brief description of what changes were made.

## What is a Pull Request?
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

## What is a Merge Conflict?
A merge conflict is an event that occurs when Git is unable to automatically resolve differences in code between two commits. When all the changes in the code occur on different lines or in different files, Git will successfully merge commits without your help. However, when two commits modify the same line of code, Git will be unable to resolve the differences on its own.

## What is a Fork?
A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

## What is a Clone?
A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. With your clone you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. It is, however, connected to the remote version so that changes can be synced between the two. You can push your local changes to the remote to keep them synced when you're online.

## How configure GitHub?
To configure GitHub, use the following commands:
```bash
git config --global user.name "Your Name"
git config --global user.email "
```

## Git Commands
1. `git init` - This command is used to start a new repository.
2. `git clone` - This command is used to obtain a repository from an existing URL.
3. `git add` - This command adds a file to the staging area.
4. `git commit` - This command records the file snapshots permanently in the version history.
5. `git status` - This command shows the status of changes as untracked, modified, or staged.
6. `git branch` - This command lists all the local branches in the current repository.
7. `git checkout` - This command is used to switch from one branch to another.
8. `git merge` - This command is used to merge the changes from one branch to another.
9. `git push` - This command is used to send the committed changes of the master branch to your remote repository.
10. `git pull` - This command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.
11. `git log` - This command is used to list the version history for the current branch.

## GitHub Commands
1. `git remote add origin` - This command is used to link your local repository to the remote repository.
2. `git push -u origin master` - This command is used to push the changes to the master branch of your remote repository.
3. `git pull origin master` - This command is used to pull the changes from the master branch of your remote repository.
4. `git clone` - This command is used to obtain a repository from an existing URL.
5. `git remote -v` - This command shows the URL of the remote repository.

### How create a new branch and switch to it?
To create a new branch and switch to it, use the command `git checkout -b <branch>`.
```bash
git checkout -b <branch>
```

### How to delete a branch?
To delete a branch, use the command `git branch -d <branch>`.
```bash
git branch -d <branch>
```

### How to undo a commit?
To undo a commit, use the command `git reset --soft HEAD^`.
```bash
git reset --soft HEAD^
```

### How move the changes from a branch to another?
To move the changes from a branch to another, use the command `git cherry-pick <commit>`.
```bash
git cherry-pick <commit>
```

### How to remove a commit that has been pushed to the remote repository?
To remove a commit that has been pushed to the remote repository, use the command `git revert <commit>`.
```bash
git revert <commit>
```

### How to remove a commit that has not been pushed to the remote repository?
To remove a commit that has not been pushed to the remote repository, use the command `git reset --hard <commit>`.
```bash
git reset --hard <commit>
```

### How to remove a commit that has been pushed to the remote repository and you want to keep the changes?
To remove a commit that has been pushed to the remote repository and you want to keep the changes, use the command `git reset --soft <commit>`.
```bash
git reset --soft <commit>
```

### How to remove a commit that has been pushed to the remote repository and you want to discard the changes?
To remove a commit that has been pushed to the remote repository and you want to discard the changes, use the command `git reset --mixed <commit>`.
```bash
git reset --mixed <commit>
```

### How to remove a commit that has been pushed to the remote repository and you want to keep the changes in the staging area?
To remove a commit that has been pushed to the remote repository and you want to keep the changes in the staging area, use the command `git reset <commit>`.
```bash 
git reset <commit>
```

## What is staging area?
The staging area is a place where you can group changes before committing them to the repository.

### How to remove a commit that has been pushed to the remote repository and you want to keep the changes in the working directory?
To remove a commit that has been pushed to the remote repository and you want to keep the changes in the working directory, use the command `git reset --mixed HEAD`.
```bash
git reset --mixed HEAD
```

### How to remove a file from the staging area?
To remove a file from the staging area, use the command `git reset HEAD <file>`.
```bash
git reset HEAD <file>
```

### How to remove a file from the working directory?
To remove a file from the working directory, use the command `git rm <file>`.
```bash
git rm <file>
```

### How to rename a file?
To rename a file, use the command `git mv <file-original> <file-renamed>`.
```bash
git mv <file-original> <file-renamed>
```

### How to show the changes between commits?
To show the changes between commits, use the command `git diff <commit1> <commit2>`.
```bash
git diff <commit1> <commit2>
```

### How to show the changes between the working directory and the staging area?
To show the changes between the working directory and the staging area, use the command `git diff`.
```bash
git diff
```

### How to show the changes between the working directory and the last commit?
To show the changes between the working directory and the last commit, use the command `git diff HEAD`.
```bash
git diff HEAD
```

### How to show the changes between the staging area and the last commit?
To show the changes between the staging area and the last commit, use the command `git diff --staged`.
```bash
git diff --staged
```

### How to show the changes between two branches?
To show the changes between two branches, use the command `git diff <branch1> <branch2>`.
```bash
git diff <branch1> <branch2>
```

