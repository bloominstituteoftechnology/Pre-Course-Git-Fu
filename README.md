# Pre Course Git Fu

## Terms for learning Git
 * Repository - "This is where all of my project's files and their revision histories are contained. If I own a repository I can also share ownership of grant collaborator access or give access permission. I can have unlimited repositories and can invite an unlimited number of collaborators: I can invite every person on planet earth as a collaborator and then some."

 * Git - Version Control - "A system used to track changes to my files or set of files, coordinate work on said files by others. A distributed revision control system that is all about speed, data integrity, and supporting distributed non-linear workflows."

 * Clone - "A copied repository stored on my local area or on my computer which can then be synced between two locations."

 * Fork - "This is a copied repository that I manage. I can manage changes to a project without affecting the original (upstream) repository. I can get updates or submit changes with pull requests. With open source projects, I can iterate on ideas before I initiate a pull request so that the upstream respository gets updated and everyone benefits."

 * History - "A log that contains all of the previous commits to a project."

 * Staging - "Readying a modified file using the git add command so that it can be committed to my forked repository."

 * Remote - "A url where my code is stored. The url could be my own repository or another user's fork, or on a different server."

 * Commit - "After staging a file using the git add command, commiting it with the git commit command stores in in my local database. If this file is found in the Git directory, it has been committed."

 * Push - "Using the git push command moves my commits from my local branch to a remote repository."

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`