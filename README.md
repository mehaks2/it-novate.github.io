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
 

 git fetch origin(from github to local)
 git merge origin/master(from github to local)
 git pull origin(from github to local)
 
 git push origin (from locat to github)
 git push origin main (main is Branch Name)
 git pull (get the all the branch and data from github)
 git brnach (shows the all branches on local)
 git branch -a(show on  all branches on github and local)
 git branch -r(show on  all branches on github)
 
 
 git reset:==git reset is a powerful command that is used to undo local changes to the state of a Git repo


git remote set-url origin https://github.com/mehaks2/learnerGit.git WHEN error: remote origin already exists.
git push origin main WHEN  error: failed to push some refs to 'https://github.com/mehaks2/learner.git'
git pull origin main --allow-unrelated-histories WHEN unable to push the data..fatal: refusing to merge unrelated histories

