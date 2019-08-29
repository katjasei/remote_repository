   1 git clone https://github.com/mattpe/git-intro.git local_repo
   2 cd local_repo
   3 git remote set-url origin https://github.com/katjasei/remote_repository.git
   4 git remote -v
   5 git remote add origin https://github.com/katjasei/remote_repository.git
   6 git push -u origin master
   7 history
   8 git add notes.md
   9 git commit -m "new file notes.md is added"
  10 git push -u origin master