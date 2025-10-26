# touble_shooting_issues

# * Creating a SSH Key for -  Permission denied (publickey). fatal: Could not read from remote repository. <br />

To SSH to GitHub  <br />
1 - create repo on GitHub  <br />
2 - git clone git@github.com:epifeni/Python_Funtions.git  <br />
3 - Start the ssh-agent in the background  <br />
4 - nano ~/.ssh/config  <br />
5 - open ~/.ssh  <br />

https://www.youtube.com/watch?v=TviP5rCZiy0  <br />
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent  <br />

# * Add the URL of the remote server to local repo  <br />
git remote add origin https://github.com/epifeni/touble_shooting_issues.git  <br />

# * Pull from GitHub to Local Repo  <br />
Go into the folder on the local computer  <br />
git init  <br />
git clone -b master https://github.com/epifeni/touble_shooting_issues.git --- this will clone the remote files into the local folder  <br />
https://www.youtube.com/watch?v=Ow8jA-LAtak  <br />

# * Pushing to GitHub  <br />
git init  <br />
git add .  <br />
git commit -m "Any Commit message or info."  <br />
git branch -m main  <br />
git push -u origin main  OR git push origin main  <br />
https://how.dev/answers/how-to-push-an-existing-project-to-github-using-git  <br />

# * Pulling from remote to local repo <br />
git pull  OR git pull origin main  <br />

# * Rebase repo <br />
git pull --rebase origin main <br />

