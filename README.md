# Learning Git (Distributed Version Control)
# Keeping History of working versions of project
# Know who make changes and why and when 
# Merge conflicting changes
# https://git-scm.com/



sun01$ echo "# learninggit" >> README.md


sun01$ git init



sun01$ git add README.md




sun01$ git commit -m "first commit"



sun01$ git remote add origin https://github.com/amitsuneja/learninggit.git



sun01$ git push -u origin master

Username for 'https://github.com': amitsuneja

Password for 'https://amitsuneja@github.com':






sun01$ git clone https://github.com/amitsuneja/learninggit.git

sun01$ cd learninggit

sun01$ mkdir dir1

sun01$ touch dir1/file1


sun01$ git add dir1

sun01$ git add dir1/file1



sun01$ git commit -am "My 6th commit"



sun01$git push

Username for 'https://github.com': amitsuneja

Password for 'https://amitsuneja@github.com':



















# Making Git Passwordless

Login to EC2
use ssh-keygen
cat ~/.ssh/id_rsa.pub

login to GitHub > Profile > SSH and GPG Keys > New ssh Key > GiveTitel and SaveKey 

sun01$ git remote show origin
* remote origin
  Fetch URL: https://github.com/amitsuneja/learninggit

  Push  URL: https://github.com/amitsuneja/learninggit



sun01$ git remote set-url origin git+ssh://git@github.com/amitsuneja/learninggit


sun01$ git remote show origin
* remote origin
  Fetch URL: git+ssh://git@github.com/amitsuneja/learninggit


  Push  URL: git+ssh://git@github.com/amitsuneja/learninggit
