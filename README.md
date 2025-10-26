# touble_shooting_issues

# * Creating a SSH Key for -  Permission denied (publickey). fatal: Could not read from remote repository.

To SSH to GitHub
1 - create repo on GitHub  
2 - git clone git@github.com:epifeni/Python_Funtions.git  
3 - Start the ssh-agent in the background  
4 - nano ~/.ssh/config  
5 - open ~/.ssh  

https://www.youtube.com/watch?v=TviP5rCZiy0  
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent  

# * Add the URL of the remote server to local repo  
git remote add origin <linkToEmptyRepo>  

# * Pull from GitHub to Local Repo
Go into the folder on the local computer
git init
git clone -b master https://github.com/epifeni/touble_shooting_issues.git --- this will clone the remote files into the local folder
https://www.youtube.com/watch?v=Ow8jA-LAtak

# * Pushing to GitHub
git init
git add .
git commit -m "Any Commit message or info."
git branch -m main
git push -u origin main
https://how.dev/answers/how-to-push-an-existing-project-to-github-using-git
