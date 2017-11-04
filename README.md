# Pre Course Git Fu

## Terms for learning Git
 * Repository - "The purpose of Git is to manage a project, or a set of files, as they change over time. Git stores this information in a data structure called a repository. A git repository contains, among other things, the following: A set of commit objects. A set of references to commit objects, called heads."
 * Git - Version Control - Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later
 * Clone - git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository. ... Cloning a local or remote repository. Cloning a bare repository. - Basically copy paste to a new folder that I can submit later. 
 * Fork - A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project. Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.
 * History - These changes are imported as added development branches, and can be merged in the same way as a locally developed branch. ... The Git history is stored in such a way that the ID of a particular version (a commit in Git terms) depends upon the complete development history leading up to that commit.
 * Staging - The name "staging" for the git feature derives from this meaning: When staging, you are preparing and organizing a commit. 
 * Remote - A remote in git is basically a bookmark for a different repository from which you may wish to pull or push code. The bookmarked repository may be on your local computer in a different folder, on remote server, or it may even be the repository itself ( I haven't tried this ) but the simplest analogy is a bookmark.
 * Commit - Well, basically git commit puts your changes into your local repo
 * Push - git push "updates remote refs along with associated objects". 

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`


Csaba Balogh
