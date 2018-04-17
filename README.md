# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - A directory or storage space where your projects can live. Sometimes GitHub users shorten this to “repo.” It can be local to a folder on your computer, or it can be a storage space on GitHub or another online host. You can keep code files, text files, image files, you name it, inside a repository.
 * Git - Version Control - Basically, the purpose Git was designed to serve. When you have a Microsoft Word file, you either overwrite every saved file with a new save, or you save multiple versions. With Git, you don’t have to. It keeps “snapshots” of every point in time in the project’s history, so you can never lose or overwrite it.
 * Clone - Cloning a git repository means that you create a local copy of the code.
 * Fork - How do multiple people work on a project at the same time without Git getting them confused? Usually, they “branch off” of the main project with their own versions full of changes they themselves have made. After they’re done, it’s time to “merge” that branch back with the “master,” the main directory of the project.
 * History - Git stores history as a graph of snapshots of the entire repository. These snapshots—which are called commits in Git—can have multiple parents, creating a history that looks like a graph instead of a straight line.
 * Staging - Staging is a step before the commit process in git. That is, a commit in git is performed in two steps: staging and actual commit.
 * Remote - A remote URL is Git's fancy way of saying "the place where your code is stored." That URL could be your repository on GitHub, or another user's fork, or even on a completely different server.
 * Commit - This is the command that gives Git its power. When you commit, you are taking a “snapshot” of your repository at that point in time, giving you a checkpoint to which you can reevaluate or restore your project to any previous state.
 * Push - If you’re working on your local computer, and want your commits to be visible online on GitHub as well, you “push” the changes up to GitHub with this command.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
