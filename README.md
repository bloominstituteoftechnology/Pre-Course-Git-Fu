# Pre Course Git Fu

## Terms for learning Git
 * Repository - The purpose of Git is to manage a project, or a set of files, as they change over time. Git stores this information in a data structure called a repository. A git repository contains, among other things, the following: A set of commit objects. A set of references to commit objects, called heads.

 * Git - Version Control - Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

 * Clone - Clones a repository into a newly created directory, creates remote-tracking branches for each branch in the cloned repository (visible using git branch -r), and creates and checks out an initial branch that is forked from the cloned repository’s currently active branch.

 * Fork - A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project. Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

 * History - Git represents history in a fundamentally different way than centralized version controls systems (CVCS) such as Team Foundation Version Control, Perforce, or Subversion. Centralized systems store a separate history for each file in a repository.  Git stores history as a graph of snapshots of the entire repository. These snapshots—which are called commits in Git—can have multiple parents, creating a history that looks like a graph instead of a straight line. After you have created several commits, or if you have cloned a repository with an existing commit history, you’ll probably want to look back to see what has happened. The most basic and powerful tool to do this is the git log command.

 * Staging - The staging area is a file, generally contained in your Git directory, that stores information about what will go into your next commit. 

 * Remote - Remote repositories are versions of your project that are hosted on the Internet or network somewhere. Remote repositories can be on your local machine.

 * Commit - Stores the current contents of the index in a new commit along with a log message from the user describing the changes.

 * Push - Updates remote refs using local refs, while sending objects necessary to complete the given refs.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`