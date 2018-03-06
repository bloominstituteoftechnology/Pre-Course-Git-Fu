# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - Git stores this information in a data structure called a repository. A git repository contains, among other things, the following: A set of commit objects. A set of references to commit objects, called heads.
 * Git - Version Control - A system for tracking changes in computer files and coordinating work on those files among multiple people.
 * Clone - a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository.
 * Fork - A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project. Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.
 * History - After you have created several commits, or if you have cloned a repository with an existing commit history, you'll probably want to look back to see what has happened. (git log command)
 * Staging - Staging is a step before the commit process in git. 
 * Remote - A remote in git is basically a bookmark for a different repository from which you may wish to pull or push code.
 * Commit - Basically git commit "records changes to the repository."
 * Push - git push "updates remote refs along with associated objects".

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
