# Pre Course Git Fu

## Terms for learning Git
 * Repository - Basically the directory where all of a projects files are organized and changes are stored.
 * Git - open source program that tracks changes in text files. Version Control - Git is one of the multiple programs used for version control which is how a group of contributors can go back to any point in the history of making and changing files in the project to see who made changes and what those changes were.
 * Clone - a copy of the repository that sits on my local computer that is connected to the repository so that changes can be synced between the local and the remote copy.
 * Fork - Personal copy of the repository that lives in my account.  I can make pull requests of the original author from my fork
 * History - record of changes made to files
 * Staging - Saving changes to the cloned copy and preparing to commit to the remote repository
 * Remote - The version of a cloned copy that is stored on a server so that changes to the clone can be synced with the remote
 * Commit - an individual change to a file usually accompanies with a message from the owner of the changes that briefly describes the changes being made. Each commit has it's own unique ID which git uses to track who made what changes.
 * Push - How you upload changes to the repository once you have committed those changes.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`