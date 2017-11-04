# Pre Course Git Fu

## Terms for learning Git
 * Repository - Metaphor used: project folder. Repo contains all files, versions and revision history. Can have multiple collaborators.
 * Git - Version Control - Git is one option to keep track of revisions made and track them, allowing a flexible approach to make and un-make changes by multiple parties.
 * Clone - Verb: Make an identical copy of a repo to store it on the local device instead of web server. Noun: the identical copy that is made.
 * Fork - To make a copy of a user's repository to then make changes without affecting the original user's repo. First user still has the original, but additional user[s] get to make changes to the fork they've taken ownership of before deciding if/when to send any changes they've made back to the original user.
 * History - The timeline of uniqueIDs and comments created during each commit that allows the user[s] to go back to earlier versions and to track all changes.
 * Staging - Collects information about the working directory that is getting ready to be committed.
 * Remote - The version of the repository that is stored on the server (as opposed to on a local device).
 * Commit - Creating a record of a change (along with a unique ID) in order to track changes. This is the way in which version control allows user[s] to backtrack, if necessary, to previous versions of a file or project.
 * Push - The process of sending one's changes on the the locally stored clone to the remote repository.

 >I have had a few frustrating experiences with Git at a few different Hackathons. Frustrating, because I didn't know how to use it effectively (or at all, really), and didn't have the time to ask for help  in the short period of time the Hackathon afforded.
 >I'm looking forward to building skills using Git, and getting involved with contributing to Open Source projects.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
8. create a pull request on GitHub