# Pre Course Git Fu

## Terms for learning Git
 * Repository - A repository (also, "repo") is an area within GitHub or local to a computer where projects and their associated code/revisions/etc. are found.
 * Git - Version Control - Git is a software that facilitates version control. Version control is a systematic way of allowing several people work on different parts of the same project and then dovetailing the changes into an updated version. 
 * Clone - A clone is code taken from a person or organization that is CC'ed locally so that it can be edited without altering the original product.
 * Fork - Fork is the step before cloning. It involves duplicating the code from one repository and moving it to your own. After Forking, cloning takes place by grabbing the URL and entering it via command line so that the code resides locally.
 * History - Meticulous notes taken as part of Git's Version Control system that acts as footprints, showing the path the improvements took so the process can be inspected later if anything runs afoul.
 * Staging - Staging is sort of a rough draft of the code editing process. You have made progress and would like to save it, but still understand there is more work to be done before it can be committed. Staged code is signified by a red file name in VS Code.
 * Remote - URL where code is stored - typically from a GitHub repository or from forking.
 * Commit - An manual action made after code has been edited locally and something has been accomplished. It acts as a save point that can be revisited if need be. Signified by green text in VS Code. This step also requires making a note of what changes were made.
 * Push - Action taken when finished editing locally. This pushes the code back online onto GitHub under your personal GitHub account. This doesn't mean it is pulled into the original code that was forked, just your personal version of that original code. Another step must be taken to meld changes with the original.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`