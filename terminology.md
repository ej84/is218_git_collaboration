# Terminology  
1. Repository: Basic element of GitHub and can be considered the folders for a project. 
A repository contains all of the project files (including documentation), and stores each file's revision history. 
Repositories can have multiple collaborators and can be either public or private.  
2. Clone: A copy of a repository that lives on a local computer rather than on a website's server.
Changes made to this local copy can be pushed to the remote version.  
3. Fork: A copy of another user's repository that lives on your account. This allows you to make changes
without affecting the original upstream repository. Forks can also be kept up to date with the
latest changes using a pull request.  
4. Branch: A parallel version of a repository. A branch exists and can be modified without
affecting or disrupting the main branch. Changes made in a branch can be merged back into
the main branch.  
5. Commit: An individual change to a file (or set of files), also known as a 'revision'. When a commit is made, 
Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the 
specific changes committed along with who made them and when. Commits usually contain a commit message 
which is a brief description of what changes were made.  
6. Merge: To take changes from one branch (in the same repository or from a fork), and apply them into another.
Merges often occur as a 'pull request'. Merges can be done the command line or the GitHub website itself.  
7. Checkout: Used to create a new branch, change your current working branch to a different
one, or to switch to a different version of a file from a different branch. Checkout also
updates all or part of the working tree with a tree object or blob from the object database,
and updates the index and HEAD if the whole working tree is pointing to a new branch.  
8. Push: To send committed changes to a remote repository on GitHub.com.  
9. Pull: To retrieve changes made to a remote file and apply them to your local copy,
can be considered 'updating' your local file.  
10. Remote Add/Remove/Show: Used to manage repositories that are hosted on the Internet or
another network.  
11. Status: Lists the files you have changed and those that you still need to add/or commit  
12. Master Branch: Created by the 'git init' command and is the default branch for a project.