# Pre Course Git Fu

## Terms for learning Git
 * Repository - A folder that contains all of a particular projects files and revision history.
 * Git - Version Control - A system that records all project changes in a file or set of files for the purpose of future recall and analyzation.  
 * Clone - A editable copy of a repository on a seperate computer from the copy inhabiting the initial server.
 * Fork - A personal of a repository on a user account that allows pull request comparison to the original copy. 
 * History - The record of all changes that have been made to a particular project by users over time. 
 * Staging - The step of repository change in which a file is being prepared for the final action of commit. 
 * Remote - The version of a project hosted on a server such as GitHub which allows syncing to all clones. 
 * Commit - An individual change to a particular file accompanied by a hash ID for aid in future editing and reversion to previous states. 
 * Push - The action of sending a commited change to a repository. 

## Steps to our Lambda School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`