# Task 2 -> Done 

# 📚 Essential Git Commands Cheat Sheet

A quick reference guide for essential Git commands, covering everything from setting up your environment to managing branches and pushing code to GitHub.

## ⚙️ 1. Configuration
Set up your Git identity before you start committing.

* `git config --global user.name "Your Name"`  
  Sets your global username for all Git commits.
* `git config --global user.email "youremail@example.com"`  
  Sets your global email address for all Git commits.

## 🚀 2. Getting Started & Status
Initialize repositories and keep track of your file states.

* `git init`  
  Initializes a new, empty Git repository in your current directory.
* `git status`  
  Shows the status of your working directory and staging area (lets you see what has been modified, staged, or is untracked).

## ➕ 3. Staging & Committing
Save your progress to the local repository.

* `git add <file name>`  
  Adds a specific file to the staging area.
* `git add .`  
  Adds all modified and new files in the current directory to the staging area.
* `git commit -m "your commit message"`  
  Saves your staged changes to the local repository with a descriptive message.

## 📜 4. Commit History
Review the history of your project.

* `git log`  
  Displays the full commit history, including the author, date, and full commit message.
* `git log --oneline`  
  Displays a condensed version of the commit history (one commit per line), making it easier to scan.

## 🌿 5. Branching & Merging
Manage different feature streams or versions of your project.

* `git branch`  
  Lists all the local branches in your repository.
* `git branch <branch_name>`  
  Creates a new branch with the specified name.
* `git checkout <branch_name>`  
  Switches your working directory to the specified branch.
* `git merge <branch_name>`  
  Merges the specified branch's history into your current active branch.

## ☁️ 6. Remote Repositories (GitHub)
Connect your local work to the cloud.

* `git remote add origin <remote_repository_URL>`  
  Connects your local repository to a remote server (like GitHub). *(Note: replace `<remote_repository_URL>` with your actual repo link).*
* `git push -u origin master`  
  Pushes your committed changes to the `master` branch of the remote repository (the `-u` flag sets the upstream tracking for future pushes).
