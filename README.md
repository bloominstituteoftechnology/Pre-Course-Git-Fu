# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * **Repository** - a collection of data about your file history, tracks changes and contains the current and past commits in your file 
 * **Git - Version Control** - An example of a distributed version control system, which is a system that tracks changes to a project over time. The distributed aspect means that the entire file project is "mirrored" on local machines, and not solely stored on a central server
 * **Clone** - To create a mirrored project from a main repo on your local machine
 * **Fork** - to create a remote repo of a project you are working on so you don't mess up the main repo
 * **History** - The data that shows changes in a project over time, including commit data
 * Staging - staging is adding the changed files you want to commit to your repo
 * **Remote** -  a remote repo is a repo separate from the working directory where you can share them with a team or push your changes
 * **Commit** - this is adding changes to the repo. You commit changes in distinct, small pieces so that your work is incrementally saved and if you introduce code that breaks something you can revert back to a prior "commit" without losing anything. Commits are usually accompanied by a short, descriptive note above the changes you made to the file
 * **Push** - push tells Git that you want to move your changes upstream, in Lambda workflows case we push our changes to the master branch of our remote repo so we can add a pull request to the Lamba repo and submit our assignments

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
