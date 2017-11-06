# Pre Course Git Fu

## Terms for learning Git
 * Repository - A repository is comparable to a folder, it is the place where all of the project files are stored with a history of their revisions.
 * Git - Version Control - Git is a version control system. It is an open source program for tracking changes in text files. A version control system allows multiple people to work on the same project -even if they are not physically close. It allows them to make changes for review without changing the entire project.
 * Clone - A clone is a copy of a repository that is on your computer instead of a website's server. When you make a clone you can edit the files in whatever editor you want and use Git to keep track of these changes without being online.
 * Fork - A fork is a personal copy of another users repository that lives on your account. This allows you to make changes without effecting the original.
 * History -the entire history of a project is represented as a set of interelated commits. 
 * Staging - Staging refers to getting a file ready to make a commit.
 * Remote -  The version of something that is hosted on a server, it can be connected to local clones so that changes can be synced.
 * Commit - a commit is an idividual change to a file or a set of files. its like a revision. Commits allow you to keep a record of what changes where made and by who( they usualy cotian a message that briefly details the changes made.)
 * Push - when you Push your commited changes it sends them to a remote repositry, this allows others to access the changes you made.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`