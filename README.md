# Pre Course Git Fu

## Terms for learning Git
 * Repository - A repository is a data structure where the full history of your work is stored.
 * Git - Version Control - Git is a free and open source distributed VCS designed to handle large projects with speed and effiency and to store data like a series of snapshots. 
 * Clone - Clone creates a copy of the existing repository to a new directory (command is "git clone").
 * Fork - A fork is a copy of a repository and enables you to make changes to it without affecting the original project.
 * History - Git stores history as a stream of snapshots (known as commits) of the entire repository. 
 * Staging - To stage a file is to prepare and organize it for a commit, and staging allows the user more control over how they want to approach version control.
 * Remote - Remote repositories are versions of your project hosted at a location different from the one on your local disk. 
 * Commit - "git commit" records your changes to the local repository.
 * Push - "git push" transfers the last changes/commits to a remote repository.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`