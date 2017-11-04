# Pre Course Git Fu

## Terms for learning Git
 * Repository - a place where the history of your work is stored. It often lives in a .git subdirectory of your working copy - a copy of the most recent state of the files you're working on.

 * Git - Version Control - a system for tracking changes in computer files and coordinating work on those files among multiple people.

 * Clone -  create a local copy of the code provided by developer.

 * Fork - (take the source from someone's repository at certain point in time, and apply your own diverging changes to it), you would clone the remote repository to create a copy of it, then do your own work in your local repository and commit changes.

 * History - A record of each file's revisions as committed by developers

 * Staging - the act of preparing and organizing a commit.

 * Remote -the version of something that is hosted on a server, most likely GitHub. It can be connected to local clones so that changes can be synced.

 * Commit - an individual change to a file (or set of files). It's like when you save a file, except with Git, every time you save it creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of what changes were made when and by who.

 * Push -  sending your committed changes to a remote repository, such as a repository hosted on GitHub.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`