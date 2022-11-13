# 👉🏻 Git-Commands-and-Workflow
### Below I have listed the correct ways to use and collaborate on github...
## 🤔 Q. How to upload my project from my computer to github?
 1) Make sure that you have GitBash installed and connected to your Github account. You can find many YouTube videos on how to do this.
 2) Open your local project folder using GitBash
 3) `git init` use this command to initialize your repository. 
 4) `git add .` use this command to add your files into git.
 5) `git commit -m "put a comment here"` this command will add a comment so that yo later know what was the commit about. 
 6) `git branch -M main` This command will set the branch to main.
 7) `git remote add origin https://yourgithubrepo.git` This will add your github repo link to remote and thus link it to your local repo.
 8) `git push -u origin main` This is final command to push all the files online inside the repo.
 9) Once this is done, you just need to do 4th, 5th and 8th command in order everytime to update the online repository with any changes in local repo.
-------------------------------------------------
## 🤔 Q. How to collaborate on someone else's repo?
 1) Fork the repo that you wish to collaborate on.
 2) Clone this forked repo into your local computer using GitBash command `git clone forkedrepolink.git`
 3) Then connect your local repo to main repo using: `git remote add upstream mainrepolink.git`
 4) `git fetch upstream` use this command and `git rebase upstream/main` this one to sync main repo and local repo.
 5) Make changes into local repo --> Push changes into forked repo --> Send Pull Request to main repo
