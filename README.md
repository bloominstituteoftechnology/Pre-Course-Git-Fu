# Pre Course Git Fu

## Terms for learning Git
 * Git has three main directories: 
   1 Working directory
   2 Staging directory
   3 Repository
 * Repository - In simplest terms a Git repository is a place where the 
   history of a project lives; technically it is a data structure
   containing a set of commit objects as well as references to these 
   commit objects called heads.
 * Git - Version Control - Version control is a system for tracking changes
   made to project files in a way that allows coordination between multiple 
   people working on a single project at the same time.
 * Clone - A git clone is a copy of a Git repository, often cloned locally on
   one's machine for remote development.
 * Fork - A fork is also a copy of a repository, different than a clone in
   that it is usually a starting point for a developer desiring to propose
   changes to someone else's project.
 * History - The history of all the different commits made to the repository.
 * Staging - In Git before a change is committed it has to be staged; the 
   change must first go to the staging directory.
 * Remote - Where a developer's unique version of the code is stored.
 * Commit - After a change is staged it is committed
 * Push - Like the name, git push pushes commits made to a local branch up to
   your remote directory.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
