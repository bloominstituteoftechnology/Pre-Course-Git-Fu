# Pre Course Git Fu

## Terms for learning Git
 * Repository - A set of files for a project and records of their changes over time
 * Git - Version Control - Distributed management of files with discrete rollback points
 * Clone - Copies project files into a new directory and links with Git Version Control
 * Fork - Copies an entire repository, allowing changes that do not affect the original master version
 * History - A record of changes made to a project and whether they are staged for committing
 * Staging - Changes made to a file are confirmed by adding the file to the stage before committing
 * Remote - A remote repository is hosted on a different computer than the one working with the code
 * Commit - Saves staged changes with a log message
 * Push - Saves committed changes on the local machine to the remote repository

## Steps to our Lambda School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`