# touble_shooting_issues

# Creating a SSH Key for -  Permission denied (publickey). fatal: Could not read from remote repository. <br />

To SSH to GitHub  <br />
1 - create repo on GitHub  <br />
2 - git clone git@github.com:epifeni/Python_Funtions.git  <br />
3 - Start the ssh-agent in the background  <br />
4 - nano ~/.ssh/config  <br />
5 - open ~/.ssh  <br />

https://www.youtube.com/watch?v=TviP5rCZiy0  <br />
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent  <br />

# Linking local and remote repos  <br />
git remote add origin https://github.com/epifeni/touble_shooting_issues.git  <br />

# Pull from GitHub to Local Repo  <br />
Go into the folder on the local computer  <br />
git init  (initialise local repo) <br />
git clone -b master https://github.com/epifeni/touble_shooting_issues.git --- this will clone the remote files into the local folder  <br />
https://www.youtube.com/watch?v=Ow8jA-LAtak  <br />

# Pushing to GitHub  <br />
git init  <br />
git status  
git add . (stage all changes in the current directory) OR git add Example.md <br />
git commit -m "initial commit"  <br />
git branch -m main  <br />
git push -u origin main  OR git push origin main OR git push (Push changes to the remote repo)  <br />
---- git push --set-upsteam origin main  (Creates the main branch in a new Git remote repo)
https://how.dev/answers/how-to-push-an-existing-project-to-github-using-git  <br />

# Pulling from remote to local repo <br />
git pull  OR git pull origin main  (pulling changes to the local repo) <br />

# Rebase repo <br />
git pull --rebase origin main <br />

# Status of the repo
git status

# Check status
git status
git status --list

# Check for changes
git diff
git diff --cache (shows staged changes)

# Getting Unstuck
press "q" key
type "clear"

# Changing file names
git mv gitStatusDemo.md newStatus.md (change the name of a file) -- changes will be updated in the staging area so no need for git add 

# Git does not track empty folders
.gitkeep (ad this file to an empty forder to track changes)

# Going back to a previous commit (rollback)
git restore --stage First_Folder/NewName.md (specify the file to be removed from staging)
git restore --stage . (removes all files from the staging area)
git restore . (wipes out all uncommited changes in one go)

# View commit history
git log (press spacebar to see more logs, press "q" to escape back to the command promt)
git show paste_the_commit_id (this shows the changes of a specific commit)
git log -p (press spacebar to see more logs, press "q" to escape back to the command promt)
git log --oneline (shorter, more readable and compact log history)
git log --grep='Example' (searches for the keyword in the commit message)
git log --branches (when using branches)

# Moving between branches 
git log --oneline
git checkout paste_the_commit_id (shows the older version of that commit - this is an older version of the project)
git checkout main (go back to the main branch)

# Revert commits



