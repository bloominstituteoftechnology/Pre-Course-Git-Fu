# Pre Course Git Fu

## Terms for learning Git
 * Repository - Is a data structure used to save commits, changes, and version for Git. A place where your work history is saved. 
 * Git - is a revision control system that allows you to manage your source code history. You do not need GitHub to use Git on your computer. 
 Version Control - By keeping a history of the changes, you can go back to other working versions to fix bugs or other problems. 
  Allows us as developers to save a master copy of our project somewhere. It then allows everyone around the world working on that project to clone a version of that master copy utiliizing github. GitHub is a Git repository hosting service which offers distributed revision control. It allows developers to work off what is called a "remote". (see remote)
 * Clone - Makes a directory that duplicates everything on GitHub at the repository URL that puts it on your "remote" computer. 
 * Fork - Makes a copy of the repository to put on your personal GitHub or an orginization you belong to. Is seperate from the other working copy, and will give you a forked symbol by the name if it is a fork. 
 * History - It's all the changes that have been made to the code, files, etc. You can revert back to history if need be. When you clone a repository you get the history that checks against changes. When you have history that needs attention, it is called "dirty" history, where as when it is green it is "clean" history. 
 * Staging - When a file has changed at this "remote", you can add the change to the staging area. This means you are ready to do somnething with that change. 
 * Remote - This is your personal copy on your machine that you are making changes on. This is on your computer. 
 * Commit - This records changes made to the repository
 * Push - Allows you to publish your local commits. Updates references to this repository allowing you to push to a remote server so other people can have access to it. 

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`

