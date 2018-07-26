**Steps to add local repository to git repository**
1. cd 项目根目录
   __git init__
2. 加入仓库
   __git add *__
3. 提交
   __git commit -m "init commit"__
4. 在 github 新建一个仓库  复制仓库地址
5. 本地仓库添加远程仓库
   __git remote add origin github_repository (url)__
6. 拉取文件
   __git pull origin master__
7. 推送到远程仓库
   __git push origin master__
   

**git clone <url>**
- makes a copy of a repository
- stores it on your computer
- a 'fork' creates your own copy of someone else's repository

**git add <filename>**
- adds a file to "staging area"
- tells git to include the file in the next revision to the repository
- **git add \* ** adds all changed files

**git commit -m message**
- saves the chanes to repository as a new revision (a "commit")
- records a message
- **git commit -am "message"** adds and commits in same step

**git status**
- show current status of repository

**git push**
- sends commited changes to remmote repository
- more explicitly, could write git push origin master

**git pull**
- receives changes from remote repository

**git conflicts**
- when two different commits can't be automatically merged
- need to be resolved