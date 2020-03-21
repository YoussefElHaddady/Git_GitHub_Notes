# Git_GitHub_Notes
## Getting started with Git
### Create your first repository, then add and comit files
+ first version release date : **0.9**  *2005-07-11*
+ verify Git installation : **`git --version`**
+ `git init`
+ `git status`
+ `git add` <file/directoryName #1> <.....>
+ `git add .`
+ `git commit -m 'Initial commit'`
+ `git remote add origin https://<your-git-service-address/user/repo.git`
### Clone a repository
copy an existing Git reposirtoy from a server to the local machine
+ `git clone https://<your-git-service-address/user/repo.git` 
+ `git clone https://<your-git-service-address/user/repo.git MyFolder`
+ `git clone https://<your-git-service-address/user/repo.git .`
### Sharing Code
+ On the remote server:
```
git init --bare https://<your-git-service-address/user/repo.git
```
+ On the local machine :
```
git remote add origin https://<your-git-service-address/user/repo.git
git push --set-upstream origin master
```
## 2. Browsing the history
### 2.1. "Regular" Git Log
+ `git log`
+ `git log -2`
## 2.2. Prettier Log
+ `git log --decorate --oneline --graph`
