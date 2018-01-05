# Pre Course Git Fu

## Terms for learning Git

 * Repository -  A collection of refs together with an object database containing all objects which are reachable from the refs, possibly accompanied by meta data from one or more porcelains. A repository can share an object database with other repositories via alternate mechanisms.
 * Git - Version Control - A form of software developement allowing for developers to track changes to code and keep a history of those changes. Allowing for smoother addition of new code as well as the ability to roll back if issues occur.
 * Clone - A copy of the master repository a developer is working with.
 
 * Fork - is a branching from the master copy and contains the cloned repository with your new code edits.
 * History - A chronological log of code edits
 * Staging - Staging is having new code edits recognized, review, and ready to be added to the master.
 * Remote - "the place where your code is stored" could be on your fork, a co-workers fork, an independent server.
 * Commit - A single point in the Git History. A statement of the edits made on your clone. That is to be pushed to the master. Stores the changes you've made to your repository in your local repository.
 * Push - Update the latest commits youve made on your local repository back to the remote Master.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`