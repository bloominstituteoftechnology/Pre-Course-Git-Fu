# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - 
  A repository is a central place where files are stored for version control
 * Git - Version Control - 
   Git is a tool that allows developers to version control their files, track changes,
   and collaborate easily with other developers.
 * Clone - 
   Cloning is when you copy a repo to your development environment.
 * Fork -
   Forking is similar to cloning. However, with forking you can copy the repo of choice
   to your own repo and make changes independant of the repo you forked.
 * History -
   The history displays changes you've made to files that are not commited. When the 
    files are commited git will output a commit index which allows you to find 
   specific indexes. This allows for reverting to older commits.
 * Staging -
   You stage files by ```$git add <file.name> | .```. This places files in waiting to be commited. 
 * Remote - 
   You can work on files remote from the master.
 * Commit -
   Once files are staged with ```$git add``` typing ```$git commit -m "msg"``` will commit the files
   to your local repo.
 * Push -
   ```push``` is similar to ```commit``` but commits files to your remote repo instead of local.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`