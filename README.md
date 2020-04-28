# 2020-04-28-git-class
Git collaboration workshop

- `git clone <URL>`: downloads the repository from the web to our computer
	- make sure you don't nest this command in another repository
	- just like `git init` do this only once per repository
- `git push <where> <what>`: pushes repository to the web from computer

## Branches

- `git branch <branch_name>`: create a new branch
- `git switch <branch_name>`: move to a branch
	-`git checkout <branch_name>`: old way to moving to a branch
- `git switch -c <branch_name>`: both create and move to a branch in one command
	- `git checkout -b <branch_name>`: old way to do this
- `git pull <where> <what>`: pulls repository from github to computer

## Pull requests (Online Merge)
- `git push origin <branch_name>`: pushes branch to the remote
- don't forget to clean up your branches
- `git fetch --prune`: cleans up the references in your `git log --oneline`
- `git branch -d <branch_name>`: delete branch on your local machine


