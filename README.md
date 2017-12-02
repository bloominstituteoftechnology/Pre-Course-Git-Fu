# Pre Course Git Fu

## Terms for learning Git
 * Repository - A repository is a storehouse of data(code in the case of Git) 
 * Git - Version Control - Version Control is system used to control/monitor a set of files(code in the case of Git) in order to recall current/previous versions of Code
 * Clone - Clone copies the entire existing repository to your local workstation. However only those labeled as contributors can commit changes to the online repository through the cloned repository
 * Fork - Fork allows you to make changes to a project without affecting the original project. This allows one to propose changes or use a project as a starting point without affecting the original
 * History - History allows you to track changes made to files in a Git Repository and view versions
 * Staging - Staging allows one to choose what to commit/update the repository. This allows you to commit a finished feature, but leave out features that aren't yet ready to be added to the master project
 * Remote - This is the online repository eg. GitHub. 
 * Commit - This is the recording of changes to a repository
 * Push - Updating the online(remote) repository with changes made locally

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`