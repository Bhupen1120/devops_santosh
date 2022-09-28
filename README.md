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

git push origin :<branch name> : to delete a branch from remote repo (example "git push origin :feature/task-1")

git branch -d <branch name> : to delte the branch from local repository

Note: the difference between git fetch and git pull are, git fetch will update the references in local repo with remote repo (example: if any new branch created, or any branch is updated with new commits)
where as git pull will update the current branch content/changes

Create merge conflict scenario:

1. create branch task-1 from master

2. create branch task-2 from master

3. change a file on task-1 (local)

4. change the same file from task-2(remote,local)

5. merge task-1 to master (local,remote)

6. task-2 to master

fix: git pull origin master in to your task-2 branch

delete << and >> === lines
