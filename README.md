# Git Basics Practice Repository
This repository demonstrates the basic Git commands I practiced while learning version control and GitHub workflows.
--------------------------------------------------

FILES IN THIS REPOSITORY

README.md → Contains explanation of Git commands  
branching.md → Demonstrates Git branching practice  
merge.md → Demonstrates Git merging practice  

--------------------------------------------------

1. GIT INITIALIZATION

Initialize a new repository

git init

Check repository status

git status

--------------------------------------------------

2. ADDING FILES

Add a specific file

git add filename

Add all files

git add .

--------------------------------------------------

3. COMMIT CHANGES

Commit staged changes

git commit -m "Initial commit"

View commit history

git log

Short commit history

git log --oneline

--------------------------------------------------

4. BRANCHING COMMANDS

Create a new branch

git branch feature-branch

Switch to a branch

git checkout feature-branch

Create and switch to a new branch

git checkout -b new-feature

List all branches

git branch

Delete a branch

git branch -d branch-name

--------------------------------------------------

5. MERGING BRANCHES

Merge a branch into the current branch

git merge branch-name

Example workflow

git checkout -b feature-login
git add .
git commit -m "Added login feature"
git checkout main
git merge feature-login

--------------------------------------------------

6. REMOTE REPOSITORIES

Add remote repository

git remote add origin repository-url

View remote repositories

git remote -v

Push code to GitHub

git push -u origin main

Pull latest changes

git pull origin main

Clone a repository

git clone repository-url

--------------------------------------------------

7. RESET COMMAND

Soft reset (keeps changes staged)

git reset --soft HEAD~1

Hard reset (removes commit and changes)

git reset --hard HEAD~1

--------------------------------------------------

8. REVERT COMMAND

Undo a commit by creating a new commit

git revert commit-id

--------------------------------------------------

CONCLUSION

This repository demonstrates my understanding of Git fundamentals including initialization, staging, committing, branching, merging, and working with remote repositories.