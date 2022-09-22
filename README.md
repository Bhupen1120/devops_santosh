# devops class
learning git from github

# GIT Commands

git init: to inititalize an empty repository

git clone <repo url>: to clone the remote repository in to local machine

Example: git clone https://github.com/santhoshmail2u/devops.git

after cloning "cd reponame/directory"

git branch: to check which branh we are working on

git branch -a: to display all the branches

git checkout -b <branch name>: to create a NEW branch

Example: git checkout -b my-local-branch

git add . : to add the file (make the files in to tracking from untracked mode)

git commit -m "commit message": to Create the commit (version)

git push origin <branch name>: to push the local changes to remote repository for the respective branch

git pull origin <branch name>: to pull the branch in to current branch

git diff: to see the difference in local machine (this has to be performed before git add)

git status: to check the current status of the files in repo (like, untracked, added, any commits to be made)

git log: to view the commit information

git push --set-upstream origin <branch name>
