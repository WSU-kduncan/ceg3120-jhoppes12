# Command line git 
-status 
 -Shows status of the local repository. This status includes:
 number of local commits that have not been synced with remote (GitHub)
 list of files in local folder than are NOT being tracked by git
 list of files in local folder that have changes that need to be committed
 -git status 
-clone 
 -Used to clone an existing Reository and create a clone of it
 -git clone 
-add 
 -The add command adds a change or changes in the working directory to the staging area.
 -git add 
-rm
 -Removes files from the working tree and from the index.
 -git rm 
-commit
 -Captures a snapshot of the priject currently staged changes. 
 Committed snapshots are thought of as "safe versions of a project". 
 -git commit 
-push 
 -Uploads local repo content to the remote repo.
 -git push 
-fetch 
 -Downloads commits, files, and refs from a remote repo. Shows you the changes but does not force you to actually merge the chnages.
 -git fetch 
-merge
 -takes the current changes that have been commited and adds them into the current branch
 -git merge
-pull
 -Updates the local verion of a repo form a remote version.
 -git pull 
-branch
 -Let's you create, list, rename, and delet branches.
 -git branch branchname
-checkout
 -Let's you navigate between created branches.
 -git checkout branchname
-init
 -Creates a new git repo.
 -git int directoryname 
-remote 
 -Let's you create, view, and delete connections to other repos.
 -git remote 
## git files & folders
-.git folder
 -Contains all information that is necessary for the project and all information relating to commits.
-.gitignore file
 -A text file that tells git which files or folders to igonore in a project.
## GitHub 
-Pull requests
 -Let's you tell others about changes you've pushed to a branch in a repo.
-SSH authentication to repositories
 -Let's you connect to git hub using the secure shell protocol. It provides a secure channel over an usecured network.
## Resources
-Pro Git Book
