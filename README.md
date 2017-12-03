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
Counting objects: 3, done.
Writing objects: 100% (3/3), 227 bytes | 227.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/amitsuneja/learninggit.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
sun01$
