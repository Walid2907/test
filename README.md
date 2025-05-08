# test

this repo is for my learning about git and github !

## commands 


### 1. SETUP & CONFIGURATION
Command	Purpose  
git config --global user.name "Your Name" Set your Git username (used in commits)  
git config --global user.email "your@email.com"	Set your Git email  
git config --global -l	List all global config settings  
git config --list	List all Git config (local + global)  

### 2. STARTING A REPO
Command	Purpose
git init	Initialize a new local Git repo
git clone <url>	Clone a remote repo (creates a local copy)

### 3. STAGING & COMMITTING CHANGES
Command	Purpose  
git status	Show changed files and current branch  
git add <file>	Stage a file for commit  
git add .	Stage all changed files  
git commit -m "Message"	Commit staged changes with a message  
git commit -am "Message"	Add + commit in one step (only tracked files)  

### 4. WORKING WITH BRANCHES
Command	Purpose
git branch	List branches
git branch <name>	Create a new branch
git checkout <name>	Switch to another branch
git checkout -b <name>	Create and switch to a new branch
git merge <branch>	Merge another branch into current branch
git branch -d <name>	Delete a branch

### 5. REMOTES (GitHub)
Command	Purpose
git remote -v	Show remote URLs
git remote add origin <url>	Add a remote repo
git push -u origin main	Push the main branch (first time)
git push	Push current branch to remote
git pull	Fetch + merge changes from remote
git fetch	Download changes without merging
git push origin main   to push to github 


### 6. VIEWING HISTORY
Command	Purpose
git log	Show commit history
git log --oneline	Compact commit history
git diff	Show changes not yet staged
git diff --staged	Show changes that are staged
git show <commit>	Show a specific commit

### 7. UNDOING THINGS
Command	Purpose
git restore <file>	Undo changes in working directory
git restore --staged <file>	Unstage a file
git reset --hard	Reset all changes (⚠️ destroys local work)
git revert <commit>	Revert a specific commit with a new one

### 8. SSH & AUTHENTICATION
Command	Purpose
ssh-keygen -t ed25519 -C "email@example.com"	Generate SSH key
ssh-add ~/.ssh/id_ed25519	Add SSH key to agent
ssh -T git@github.com	Test SSH connection

### 9. ADVANCED (Optional for Beginners)
Command	Purpose
git stash	Temporarily save changes
git stash pop	Reapply stashed changes
git rebase	Rewrite commit history (advanced)
git cherry-pick <commit>	Apply a specific commit from another branch

hey i'm walid  
dada


