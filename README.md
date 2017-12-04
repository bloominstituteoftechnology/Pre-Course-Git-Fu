# Pre Course Git Fu

## Terms for learning Git
 * Repository - A repository is an organized hub of data regarding a specific development project or part of one. It holds a lot of different types of information from edits made to who made them, when, etc.
 * Git - Version Control - Git is a version control software that allows developers to essentially go back in time should something go wrong when edits are made. 
 * Clone - Cloning a repository downloads a copy to your computer.
 * Fork - Forking a repository copies it to your Git account and puts it under your name.
 * History - History refers to changes you've made and saved either to the remote on your computer or the commits pushed (defined below) to the master repository on GitHub. 
 * Staging - Staging a file is how you prepare a file to later commit it. It's the completed pile of work that has not been submitted yet.
 * Remote - A remote is the copy you make and edit when you clone or fork a repository. Just like a remote control is a control that is separate from the machine, a remote is a separate file or set of files.
 * Commit - Committing is how the user indicates the changes made thus far are important enough to keep track of in the future by saving it to the history.
 * Push - While committing is akin to saving changes, pushing is updating the fork the user has online. So, it publishes that data.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`