sun01$ echo "# learninggit" >> README.md




sun01$ git init
Initialized empty Git repository in /root/learninggit/.git/




sun01$ git add README.md




sun01$ git commit -m "first commit"
[master (root-commit) 51c656e] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md




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

