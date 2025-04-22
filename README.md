This repository is created to display the Web Application Development Mock Practical where I had to show the various command to create a repository and push code to github using git commands.

Output:

comp113@comp113:~/Desktop/TI03$ git init
Initialized empty Git repository in /home/comp113/Desktop/TI03/.git/

comp113@comp113:~/Desktop/TI03$ git add .
comp113@comp113:~/Desktop/TI03$ git remote add origin https://github.com/Anupamatilak21/LPII-Mock-Practical.git
comp113@comp113:~/Desktop/TI03$ git config --global user.name "Anupamatilak21"
comp113@comp113:~/Desktop/TI03$ git config --global user.email "anupamat.221103@gmail.com"
comp113@comp113:~/Desktop/TI03$ git commit -m "github codes"

[master (root-commit) f7f85c2] github codes
 2 files changed, 21 insertions(+)
 create mode 100644 README.md
 create mode 100644 home .html

comp113@comp113:~/Desktop/TI03$ git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 757 bytes | 757.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/Anupamatilak21/LPII-Mock-Practical.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
