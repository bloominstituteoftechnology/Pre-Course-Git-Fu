# Pre Course Git Fu

## Terms for learning Git
 * Repository - A place where your work is stored, holding history of the work
 * Git - Version Control - The type of system that git is. It's an open-source system allowing for multiple people to make changes to a single text file and keeping a history of past "versions"
 * Clone - A copy of the work at a certain point in time
 * Fork - Taking a clone and making changes to it, branching off from the original, master copy becomes a fork
 * History - The flow of different past/parent versions of a code, allowing for retraction if needed
 * Staging - First part of making a change to a file: staging can be done piecemeal as opposed to the entire section at once and is less finalized, it prepares text to be committed
 * Remote - Refers to a respository that is outside of the local files
 * Commit -The second part of making a change to a file: adds to your personal master file all of the staged material
 * Push - The final part of making a change to a file: Updates your git file repository with the localized version you just staged and committed

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`