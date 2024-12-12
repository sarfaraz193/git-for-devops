Git Commands 
# Git Commands - Simple Explanations

## Initial Setup

1. `git config --global user.name "Your Name"`: Tell Git who you are by setting your name.
2. `git config --global user.email "your.email@example.com"`: Tell Git your email so it knows how to label your changes.

## Starting a Repository

1. `git init`: Start using Git in a folder.
2. `git clone <repository_url>`: Copy a project from the internet to your computer.

## Basic Operations

1. `git status`: Check what changes you made and what needs to be saved.
2. `git add <file>`: Select a file to save.
3. `git add .`: Select all the files you changed to save.
4. `git commit -m "Commit message"`: Save your changes with a short note about what you did.

## Viewing History

1. `git log`: See the history of all your saved changes.
2. `git log --oneline`: See a quick summary of your saved changes.

## Working with Changes

1. `git diff`: See what changes you made in your files.
2. `git diff <branch_name>`: Compare your current work with another branch.

## Undoing Changes

1. `git checkout -- <file>`: Undo changes in a file.
2. `git reset <file>`: Unselect a file you added for saving.
3. `git reset --soft HEAD~1`: Undo the last save but keep your changes.
4. `git reset --hard HEAD~1`: Undo the last save and delete all changes.

## Remote Repositories

1. `git remote add origin <repository_url>`: Link your local work to a project on the internet.
2. `git push -u origin <branch_name>`: Upload your changes to the internet.
3. `git pull`: Download and combine the latest changes from the internet to your work.
4. `git fetch`: Just download the latest changes from the internet without combining them.

## Branching

1. `git branch`: See all the different versions (branches) of your work.
2. `git branch <branch_name>`: Create a new version (branch) to work on.
3. `git checkout <branch_name>`: Switch to a different version (branch) of your work.
4. `git checkout -b <branch_name>`: Create and switch to a new version (branch) in one step.
5. `git merge <branch_name>`: Combine work from another version (branch) into your current one.
6. `git branch -d <branch_name>`: Delete a version (branch) you don’t need anymore.
7. `git push origin --delete <branch_name>`: Delete a version (branch) from the internet.

---

This guide explains Git commands in very simple terms for easy understanding.
