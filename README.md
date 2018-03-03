# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
	 * Repository - A repository is simply a place where the history of your work is stored. It often lives in a git subdirectory of your working copy - a copy of the most recent state of the files you're working on.

	 * Git - Version Control - Git  is a version control system for tracking changes in computer files and coordinating work on those files among multiple people.

	 * Clone - git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository. 

	 * Fork - A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

	 * History - Git stores history as a graph of snapshots — called commits — of the entire repository.

	 * Staging - Staging is a step before the commit process in git. That is, a commit in git is performed in two steps: staging and actual commit. As long as a changeset is in the staging area, git allows you to edit it as you like.

	 * Remote - A remote URL is Git's fancy way of saying "the place where your code is stored." That URL could be your repository on GitHub, or another user's fork, or even on a completely different server.

	 * Commit - Git commit "records changes to the repository". It is used in connection with your local repository.

	 * Push - Git push is used to push commits made on your local branch to a remote repository. The git push command takes two arguments: A remote name - origin. A branch name - master.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
