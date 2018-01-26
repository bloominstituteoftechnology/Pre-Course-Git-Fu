# Pre Course Git Fu

## Terms for learning Git
 * Repository - a data structure that stores information on how a project changes over time. This includes commit objects and reference to commit objects (heads)
 * Git - Version Control - Git is the most widely used Version Control System, which is is software used to manage a project by tracking changes. You commit your work locally and then sync it with the server.
 * Clone - Copies a repository to the local machine in a specified directory
 * Fork - A personal copy of a project. Allows changes to made without effecting the original project.
 * History - A tab showing information on a commit including an optional message, timestamp, user, and user's hash ID.
 * Staging - A file in the git directory that stores information about what will go into the next commit (Also known by its technical name the "index")
 * Remote - a repository that is elsewhere, either on the internet or network
 * Commit - Stores the current contents of the staging area to the project's history
 * Push - Updates the remote repository with commits made on the local branch

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL
3. After Changes Made: `git status`
4. `git add <file-name>`
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
