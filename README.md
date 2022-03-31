# test-git-method

## clone a code
git clone [github link]

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
如果远程分支是与当前分支合并，则冒号后面的部分可以省略。直接git pull 就行\

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
git push <remote> --delete [branch name]\
example:\
git push origin --delete Jiangwei

  


  
