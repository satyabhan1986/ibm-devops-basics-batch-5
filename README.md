# ibm-devops-basics-batch-5
# Git Comands for Day-1

  478  git status
  479  git add README.md
  480  ll
  481  git status
  482  git restore --staged README.md
  483  git status
  484  git
  485  git show
  486  git
  487  git branch -a
  488  git switch -c demo
  489  git push origin demo
  490  git branch -d
  491  git branch -r
  492  git push origin --delete demo
  493  git branch -r
  494  git branch
  495  git merge demo master
  496  git
  497  git remote get-url
  498  git remote show
  499  git
  500  git --version
  501  cd /c/training/
  502  ll
  503  cd IBM/
  504  ll
  505  cd devops-basics-batch-5/
  506  ll
  507  ls
  508  git clone https://github.com/kmayer10/ibm-devops-basics-batch-5.git
  509  ll
  510  cd ibm-devops-basics-batch-5/
  511  ll
  512  cat README.md
  513  cd ..
  514  ll
  515  mkdir test-repo
  516  cd test-repo/
  517  git init
  518  git remote add origin https://github.com/kmayer10/ibm-devops-basics-batch-5.git
  519  git pull origin master
  520  git remote -v
  521  history
  522  cd ../
  523  ll
  524  cd test-repo/
  525  git config --global user.email "kulbhushan.mayer@thinknyx.com"
  526  git config --global user.name "Kul"
  527  git config --list
  528  history
  529  git status
  530  ll
  531  date >> README.md
  532  git status
  533  cat README.md
  534  git restore README.md
  535  cat README.md
  536  git status
  537  date >> training.txt
  538  git status
  539  rm -rf training.txt
  540  git status
  541  date >> training.txt
  542  git status
  543  git add training.txt
  544  git status
  545  git restore --staged training.txt
  546  git status
  547  git add training.txt
  548  git status
  549  git commit -m "adding first commit"
  550  git status
  551  date >> training.txt
  552  git status
  553  cat training.txt
  554  git restore training.txt
  555  cat training.txt
  556  date >> training.txt
  557  git status
  558  git commit -a -m "demo for triggering both commit & add together - 2"
  559  history
  560  git log
  561  git config --global user.name "kmayer"
  562  date >> training.txt
  563  git commit -a -m "showing author - 3"
  564  git log
  565  git log
  566  git log -v
  567  git log -p
  568  vi training.txt
  569  git commit -a -m "showing removal of content from file - 4"
  570  git log -p
  571  git log --oneline
  572  history
  573  git log
  574  git log -p
  575  history
  576  ll
  577  git status
  578  date > demo
  579  ll
  580  git status
  581  git commit -a -m "adding file for deletion & renaming demo" demo
  582  git add demo
  583  git commit -m "adding file for deletion & renaming demo - 5"
  584  git status
  585  ll
  586  git mv demo demo.txt
  587  ll
  588  git status
  589  git commit -m "rename demo"
  590  git status
  591  ll
  592  git rm demo.txt
  593  ll
  594  git status
  595  git restore --staged demo.txt
  596  ll
  597  git status
  598  git restore demo.txt
  599  ll
  600  git rm demo.txt
  601  git status
  602  git commit -m "file deletion demo - 7"
  603  git log --oneline
  604  git show 786d51b
  605  cat training.txt
  606  git revert 786d51b
  607  cat training.txt
  608  history
  609  git status
  610  git log --oneline
  611  git log origin/master
  612  git branch
  613  git branch -r
  614  git branch -a
  615  git status
  616  git show
  617  git branch br-1
  618  git branch -a
  619  git branch br-2 origin/master
  620  git branch -a
  621  git log --oneline
  622  git branch br-2 786d51b
  623  git branch br-3 786d51b
  624  git branch -a
  625  git log --oneline
  626  git log --oneline br-1
  627  git log --oneline br-2
  628  git log --oneline br-3
  629  git branch -a
  630  history
  631  git branch
  632  git status
  633  git log --oneline
  634  cat training.txt
  635  date >> file1
  636  git add file1
  637  git commit -m "adding file to show how folder structure changed with branch change - 9"
  638  ll
  639  cat training.txt
  640  git switch br-3
  641  cat training.txt
  642  ll
  643  git log --oneline
  644  git diff master br-3
  645  date >> file2
  646  git add file2
  647  git commit -m "branch demo - 10"
  648  git diff master br-3
  649  git log --oneline
  650  ll
  651  git log --oneline
  652  git switch br-2
  653  ll
  654  date >> file3
  655  git add file3
  656  git commit -m "branch demo - 11"
  657  git switch br-3
  658  git log --oneline
  659  git switch master
  660  git log --oneline
  661  git switch br-1
  662  date >> training.txt
  663  git add training.txt
  664  git commit -m "branch demo - 12"
  665  git log --oneline
  666  git switch master
  667  git log --oneline
  668  date >> training.txt
  669  git add training.txt
  670  git commit -m "branch demo - 13"
  671  git log --oneline
  672  git log --oneline br-1
  673  git log --oneline br-2
  674  git log --oneline br-3
  675  history
  676  git push origin master
  677  git push origin br-1
  678  git push origin br-2
  679  git push origin br-3
  680  cd ..
  681  ll
  682  cd test-repo/
  683  git remote -v
  684  cd ../ibm-devops-basics-batch-5/
  685  git remote -v
  686  git branch -a
  687  git log --oneline
  688  git pull origin master
  689  ll
  690  git log --oneline
  691  git branch -a
  692  git fetch origin
  693  git branch -a
  694  git log --oneline
  
 ===================================================================
