# Pre Course Git Fu
# 4th Nov Cs5 git homework.
## Terms for learning Git
 * Repository - The directory (usually code)that git is maintaining. There be one repository or many but you
   focus on one at a time by being in that directory on the command line or alternatively github
 * Git - Version Control - Version control is a component of software configuration management that manages
   and track changes to software source code.  
 * Clone - A clone is a copy of a repository, usually cloned from github. Local changes that you want to be
   reflected on the branch you cloned from usually need to be in the form of approved pull requests
 * Fork - A fork is an independent but linked copy of a repository where you have control over pushes to github
   and it does not change or affect the original repository you forked from
 * History - This is a log file of all the commits and changes to their repository over time
 * Staging - Staging where you let git know that you want it to track a file
 * Remote - For a given local repository the command git -v will list all the online github repositories you
   can push and pull from. Conventions says origin should be the repository you cloned from while upstream is usually the one you forked from.
   For example git remote add upstream  https://github.com/LambdaSchool/Pre-Course-Git-Fu will create the link between a local and remote repository. now I can push to and pull from the lambdaSchool repository, ie, git push upstream master (means push my changes to the master branch of the lambdaSchool repository)
 * Commit - When git saves changes to your repository.
 * Push - When git sends your local (your computer) changes to the online github project repository.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL
3. After Changes Made: `git status`
4. `git add <file-name>`
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
