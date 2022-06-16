git --version
Two way :
  1) Clone from github
     git clone https://github.com/mehaks2/learnerGit.git
     make file in folder
  2) From Desktp
     make directory
     cd directory
     git remote add origin https://github.com/mehaks2/learnerGit.git 
     git push --set-upstream origin master
 Common Step
 git status
 git add filename OR git add --all
 git commit -am "message" 'M means message. A means without staging"
 git branch master
 git checkout otherbranch
 git checkout otherbranch
 git merged otherbranch
 git branch -d otherbranch  // Delete Branch
 
 git fetch origin
 git merge origin/master
 
 git pull origin

git remote set-url origin https://github.com/mehaks2/learnerGit.git WHEN error: remote origin already exists.
git push origin main WHEN  error: failed to push some refs to 'https://github.com/mehaks2/learner.git'
