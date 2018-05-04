# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - A virtual location in which a master version of collaborative coding project is stored
 * Git - Version Control - Git is a programming system which allows users to collaborate on a central project by creating, editing and rejoining different 'versions' of a project.
 * Clone - A clone is a copy of a (usually forked) github repository intended for use on a remote or local machine
 * Fork - A fork is similar to a clone in that it is a copy of a github repository, but it is intended for interfacing with a users remote github account as opposed to simply their local machine as with a clone.
 * History - History is the record of changes to  a project or a file which are collected and maintained by git with it's version control system
 * Staging - Staging is when a edited file or group of files is prepared for commitment. In the staging area files are reviewed in order to determine which ones (in a directory) were changed and which were not. 
 * Remote - Remote may refer to a repository (or its hosting machine) that results from forking or cloning a master or origin of a repository.
 * Commit - A commit is a saved record of project changes on one's local machine. It traverses one forward along the procedural "branch" or timeline of the project workflow.
 * Push - A push is when a commit or group of commits is reflected in a user's remote repository which was forked from the origin repository. When commits or changes flow from a local machine to a remote location.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
