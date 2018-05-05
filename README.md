# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - A repository is a location, either local or remote, where the
                history of a software project is kept. It contains all the
                necessary git repository skeleton files to begin tracking the
                project contained herein
 * Git - Version Control - Git and version control is a way to keep track of
                changes made to a software program intelligently, with updates
                and previous versions stored in case they are needed
 * Clone - A clone is a copy of a repository, with all of that repositories
                projects, history and every version ever committed to the repo,
                which is then saved to your local machine
 * Fork - A fork is like a clone, but creates a copy of a repository to your
                online Github account, as opposed to a local copy.
 * History - The history of a repository includes the saved, previous versions
                of a project in the repository, as well as a log of all commits,
                comments and differences with other versions
 * Staging - Staging is when you have made a change to a repository, and you are
                in the first stages of saving it. The changes are selectively
                staged in a file within the git repository, and when you're
                ready, committed
 * Remote - A remote repository is where the code for a repository is stored
                online, be it on your github, or a fork of another user's repo,
                or wherever.
 * Commit - A commit is when the changes in the staging area are permanently
                saved to the history of the repository where you are currently
                working.
 * Push -  A push saves the recent commit to your local repository to the remote
                repository that your local repo is connected to. It updates the
                remote repository with the new changes made locally

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL
3. After Changes Made: `git status`
4. `git add <file-name>`
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
