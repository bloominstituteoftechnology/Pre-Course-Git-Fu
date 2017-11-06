# Pre Course Git Fu

## Terms for learning Git
 * Repository - A folder that contains all the project files.

 * Git - Version Control - A system that records changes to a file or set
    of files over time so that you can recall specific versions later.

 * Clone - a copy of a repository that lives on your computer instead of on     a website's server.  Also       the act of making a copy.

 * Fork - gives every developer a server-side repository, which is public.

 * History - a list of changes made; a function of the git log command.

 * Staging - an index, basically like a loading dock where you get to determine what changes get   shipped      away, since it decouples the working     directory and what actually gets saved by Git.

 * Remote - refers to a repository/set of repositories whose branches you      track.

 * Commit - the entire history of a project is represented as a set of          interrelated commits. 

 * Push -  getting the branch's head ref from a remote repository, find out     if its a direct ancestor to     the btranch's local head ref, and in that case, putting all objects, which are reachable from the          local head ref, and  which are missing from the remote repository, into the remote object database,        and updating the remote head ref.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`