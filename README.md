# github_manual

 ★将本地工程提交至github步骤：★
 1.先在网站上新建XXX.git
 
 2.然后在本地执行以下操作：
$ git init

$ git remote add origin git@github.com:Username/XXX.git


$ git pull origin master
Enter passphrase for key '/c/Users/Administrator/.ssh/id_rsa':
From github.com:Username/XXX
 * branch            master     -> FETCH_HEAD
Merge made by the 'recursive' strategy.
 .gitignore |  32 +++
 LICENSE    | 674 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 README.md  |   2 +
 3 files changed, 708 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 LICENSE
 create mode 100644 README.md
 
 查看所有文件(可选)
 $ ls -ah


 补充不需要上传的文件或文件夹列表：(可选)
$ vim .gitignore

$ git add .

$ git commit -a -m "First commit"


$ git push origin master
Enter passphrase for key '/c/Users/Administrator/.ssh/id_rsa':
Counting objects: 24, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (24/24), done.
Writing objects: 100% (24/24), 293.97 KiB | 0 bytes/s, done.
Total 24 (delta 2), reused 0 (delta 0)
To git@github.com:Username/XXX.git
   45d3e5d..0e849f5  master -> master