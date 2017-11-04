# Pre Course Git Fu

## Terms for learning Git
 * Repository - 
 	Often called a repo, a repository is a place to store code. Generally hosted in the cloud! 
 * Git - Version Control - 
 	Git(Version Control), is a type of Version Control. Version Control is a set of programs that allows a team to manage versions of files, and enables multiple people the ability to work on the same files together while maintaining complete copies of each version enivitable allowing for the compilation of work to be merged together.
 * Clone - 
 	Second thing you do to a new repo at Lambda, which downloads a copy of the remote repository locally allowing you to work on a local copy of the repository.
 
 * Fork -
 	First thing you do to a new repo. This creates a copy of the originating repository and places it in the specified new repository.
 
 * History -
 	Git history describes the pushed changes that the repository has gone through. 
 * Staging -
 	git status allow you to check on the status of the local git repository. 
 
 * Remote - 
 	Remote refers to the place where the main repository is stored. This is usually is a server setup with a repository management system running. 

 * Commit -
   When you commit you save the added(DONT FORGET TO ADD!) changes to the local copy of the git repository

 * Push -u origin master
    Push takes all of the commited changes and uploads those changes to the remote git repository.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`