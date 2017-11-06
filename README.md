# Pre Course Git Fu

## Terms for learning git
 * Repository - A git repository contains files and previous versions of those files.
 * Git - Version Control - Version control allows you to rollback to a previous version of a repository or view previous versions of files.Clone - 
  * Cloning a repository will create a local copy of the repository.Fork - 
  * Forking a repository will allow you to make changes to a copy of the repository without affecting the original repository until you make a pull request and the pull request is accepted.
 * History - The previous commits made to a repository.
 * Staging - The staging area contains files that ready to be commited to the next version of a repository. 
 * Remote - Manages the network location of the repository that allows for a project to be hosted remotely. 
 * Commit - Commits the staged changes to the repository.
 * Push - Sends the current version of your repository to a remote repository.

## Steps to our Lambda School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL
3. After Changes Made: `git status`
4. `git add <file-name>`
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`