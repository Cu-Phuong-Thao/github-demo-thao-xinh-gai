# github-demo-thao-xinh-gai
Đây là test repository thử

Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git init
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git add index.html 
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html

PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git commit -m "Add 
index.html file on github"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.name "Your Name"
to set your account's default identity.
Omit --global to set the identity only in this repository.
fatal: unable to auto-detect email address (got 'ADMIN@DESKTOP-9SG4GG1.(none)')
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git config --global user.email "thaocutp@gmail.com"
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git config --global user.name "Thao Cu"
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git log
fatal: your current branch 'master' does not have any commits yet
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git commit -m "Add index.html file"  
 1 file changed, 1 insertion(+)
 create mode 100644 index.html
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git log
commit 99c50ce9d94841218a308b5cc1483aa338851410 (HEAD -> master)
Author: Thao Cu <thaocutp@gmail.com>
Date:   Tue Nov 17 10:13:07 2020 +0700

    Add index.html file
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git remote add origin https://github.com/Cu-Phuong-Thao/github-demo-thao-xinh-gai.git
fatal: remote origin already exists.
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Cu-Phuong-Thao/github-demo-thao-xinh-gai.git'
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 260 bytes | 260.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Cu-Phuong-Thao/github-demo-thao-xinh-gai.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai> git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
PS D:\NAM44444444444\Ngon ngu kich ban _ Nodejs\github-demo-thao-xinh-gai>
