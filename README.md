# Pre Course Git Fu

## Terms for learning Git
 * Repository - contains the source code as BLOB objects, there is a local one and at least one remote one.
 * Git - Version Control - a distributed revision control and source code management system, used to manage source code updates by teams of developers that are working simultaneously.
 * Clone - creates the instance of the repository and mirrors it completely.
 * Fork - used to copy a branch of a repository.
 * History - shows a log of the commits made.
 * Staging - after an add command, the files are held in this area ready to be be made permenant on the remote repository.
 * Remote - a Git respository on another server, where permanant changes are pushed by developers.
 * Commit - holds the current state of the repository. From a given commit, you can traverse back by looking at the parent pointer to view the history of the commit.
 * Push - copies changes from a local repository instance to a remote one. Changes are made permanant.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`