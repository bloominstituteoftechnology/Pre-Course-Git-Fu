# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for Learning Git
 * Repository - A directory initialized with Git version control. All files in the repository are monitored for changes. These changes can be added to the Git history and committed to the current branch.
 * Git - Version Control - Version Control is a means of monitoring and tracking all changes made to the files in a repository. This makes it easier for people to collaborate on projects, as well as provides a failsafe in case the code breaks and needs to be reverted to a previous state.
 * Clone - A download of a repository from GitHub to your local machine. A clone copies all files in the repository to your local machine into a new directory, along with its Git history, unless otherwise specified.
 * Fork - A fork is a copy of a project repository that can be edited by the forker. The forker can submit a pull request to ask that their changes be added to the master project's repository.
 * History - Git history is a ledger of all changes, additions, deletions, comments, and commits that have occurred in the repository since its initial commit.
 * Staging - Files that are staged are files that have been changed and authorized for a commit into the current branch.
 * Remote - The address where you will be sending your git push. You can use multiple remote addresses, so that you can develop on one repository (development) without affecting the master (production).
 * Commit - Signify that changes have been made, and a comment as to what those changes were. A commit is authorization to include any changes in the current branch of the repository.
 * Push - Upload the files and their changes, along with Git history and comments, to an external repository, often the "origin" repository hosted on GitHub.

## Steps to Our Lambda School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
