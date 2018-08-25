# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - We can think of a Git repository as a directory that stores all the files, folders, and content needed for your project. What it actually is, is the object database of the project, storing everything from the files themselves, to the versions of those files, commits, deletions, et cetera. Repositories are not limited by user, and can be shared and copied.
 * Git - Version Control - Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
 * Clone - a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository.
 * Fork - Creates a copy of a repository.
 * History - allows you to see what has happened in the entirety of a repository's lifetime
 * Staging - means that git knows about the change, but it is not permanent in the repository.
 * Remote - A remote URL is Git's fancy way of saying "the place where your code is stored." That URL could be your repository on GitHub, or another user's fork, or even on a completely different server.
 * Commit - adds changes to the local repository.
 * Push - transfers the last commit(s) to a remote server.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
