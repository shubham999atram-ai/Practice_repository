# Git Basics Practice Repository
This repository demonstrates the basic Git commands I practiced while learning version control and GitHub workflows.
--------------------------------------------------

FILES IN THIS REPOSITORY

README.md → Contains explanation of Git commands  
Example folder → Demonstrates Git practice work
--------------------------------------------------

1. GIT INITIALIZATION

Initialize a new repository   -> git init

Check repository status       -> git status

--------------------------------------------------

2. ADDING FILES

Add a specific file   -> git add filename

Add all files         -> git add .

--------------------------------------------------

3. COMMIT CHANGES

Commit staged changes   -> git commit -m "Initial commit"

View commit history     -> git log

Short commit history    -> git log --oneline

--------------------------------------------------

4. BRANCHING COMMANDS

Create a new branch   -> git branch feature-branch

Switch to a branch    -> git checkout feature-branch

Create and switch to a new branch   -> git checkout -b new-feature

List all branches     -> git branch

Delete a branch       -> git branch -d branch-name

--------------------------------------------------

5. MERGING BRANCHES

Merge a branch into the current branch  -> git merge branch-name
<br>
Example workflow
<br>
git checkout -b feature-login
<br>
git add .
<br>
git commit -m "Added login feature"
<br>
git checkout main 
<br>
git merge feature-login 
<br>

--------------------------------------------------

6. REMOTE REPOSITORIES

Add remote repository    -> git remote add origin repository-url

View remote repositories -> git remote -v

Push code to GitHub      -> git push -u origin main

Pull latest changes      -> git pull origin main

Clone a repository       -> git clone repository-"url"

--------------------------------------------------

7. RESET COMMAND

Soft reset (keeps changes staged)        -> git reset --soft HEAD~1

Hard reset (removes commit and changes)  -> git reset --hard HEAD~1

--------------------------------------------------

8. REVERT COMMAND

Undo a commit by creating a new commit   -> git revert commit-id (we can get id by git log cmd)