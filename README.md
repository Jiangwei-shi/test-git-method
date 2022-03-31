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

## delete local branch
git branch -D [branch name]\
//if merged\
git branch -d [branch name]
