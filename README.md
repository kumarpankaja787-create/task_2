# 📚 Essential Git Commands Cheat Sheet

A comprehensive reference guide for everyday Git commands, covering everything from initial setup to managing remote repositories and handling branches.

## ⚙️ 1. Configuration & Setup
Set up your Git identity and bring existing projects to your local machine.

* `git config --global user.name "Your Name"`  
  Sets your global username for all Git commits.
* `git config --global user.email "youremail@example.com"`  
  Sets your global email address for all Git commits.
* `git clone <repository_URL>`  
  Creates a local copy of a remote repository on your machine.
* `git init`  
  Initializes a new, empty Git repository in your current directory.

## 🚀 2. Inspecting Your Repository
Keep track of your file states and view project history.

* `git status`  
  Shows the status of your working directory (lets you see what is modified, staged, or untracked).
* `git diff`  
  Shows the exact lines of code added or removed in your unstaged files.
* `git log`  
  Displays the full commit history, including the author, date, and full commit message.
* `git log --oneline`  
  Displays a condensed version of the commit history (one commit per line) for easy scanning.

## ➕ 3. Staging & Committing
Save your progress to the local repository.

* `git add <file_name>`  
  Adds a specific file to the staging area, preparing it to be committed.
* `git add .`  
  Adds all modified and new files in the current directory to the staging area.
* `git commit -m "Your commit message"`  
  Saves your staged changes to the local repository with a descriptive message.

## 🌿 4. Branching & Merging
Manage different feature streams or versions of your project without affecting the main code.

* `git branch`  
  Lists all the local branches in your repository.
* `git branch <branch_name>`  
  Creates a new branch with the specified name but keeps you on your current branch.
* `git checkout <branch_name>`  *(Alternative: `git switch <branch_name>`)* Switches your working directory to the specified branch.
* `git checkout -b <branch_name>` *(Alternative: `git switch -c <branch_name>`)* A handy shortcut that creates a new branch and immediately switches to it.
* `git merge <branch_name>`  
  Merges the specified branch's history into your current active branch.
* `git branch -d <branch_name>`  
  Deletes the specified branch safely (prevents deletion if unmerged changes exist).

## ☁️ 5. Remote Repositories (GitHub)
Connect your local work to the cloud and collaborate with others.

* `git remote add origin <remote_repository_URL>`  
  Connects your local repository to a remote server.
* `git push -u origin master`  *(or `main`)* Pushes your committed changes to the remote repository. The `-u` flag sets the upstream tracking for future pushes (so you can just type `git push` next time).
* `git pull`  
  Fetches the newest updates from the remote repository and immediately merges them into your current local branch.
* `git fetch`  
  Downloads the latest changes from the remote repository, but does *not* merge them into your working files automatically.
