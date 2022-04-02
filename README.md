# test-git-method

## 仓库相关
git remote -v\
仓库路径查询查询\
git remote set-url origin [remote-url]\
修改远程仓库地址\
git remote add origin [remote-url]\
添加远程仓库\
git remote rm origin\
删除指定的远程仓库

## clone a code
git clone [github link]\
git clone -b [branch name] [github link]

## create a branch in local
git checkout -b [branch name]

## chech branch
git branch -a \
for all branch \
git branch -r \
for remote branch

## switch branch
git checkout [branch name]

## update code to branch
git add .\
git commit -m "example"\
git push --set-upstrean origin [branch name]

## git pull
git pull origin master:brantest\
将远程主机 origin 的 master 分支拉取过来，与本地的 brantest 分支合并。\
git pull origin master\
如果远程分支是与当前分支合并，则冒号后面的部分可以省略。直接git pull 就行

## delete local branch
git branch -D [branch name]\
//if merged\
git branch -d [branch name]

## update branch
git pull\
git push -f origin master\
强制更新

## delete your commit content
rm -rf .git/MERGE*

## update branch
git pull\
git push -f origin master\
强制更新

## delete romote branch
git push [remote name] --delete [branch name]
example:\
git push origin --delete Jiangwei

## github issus
https://blog.csdn.net/cool99781/article/details/105821546


  
