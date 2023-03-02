### git initialization
```bash
git init
```
### check status
```bash
git status
```
### add a file to stage
```bash
git add FILE_NAME.FORMAT
```
### add all files
```bash
git add -A
```
### commit with message
```bash
git commit -m 'MESSAGE'
```
### add remote
```bash 
git remote add NAME https://github.com/USER_NAME/REPOSSITORY_NAME.git
```
### show remotes with verbose
```bash
git remote -v
```
### change branch name
```bash
git branch -M NEW_NAME
```
### add new branch
```bash
git branch BRANCH_NAME
```
### switch branch
```bash
git switch BRANCH_NAME

or

git checkout BRANCH_NAME
```
### push 
```bash
git push REMOTE_NAME BRANCH_NAME
```
### pull
```bash
git pull REMOTE_NAME BRANCH_NAME
```
### show logs
```bash
git log
```
### show file changes (HEAD means last commit)
```bash
git diff HEAD
```
### ignore changes that happen to that file
```bash
git checkout -- FILE.FORMAT
```
### show changes of staged files
```bash
git diff --staged
```
### take out that file from stage
```bash
git reset FILE.FORMAT
```
### show branches
```bash
git branch
```
### create new branch
```bash
git branch BRANCH_NAME
```
### merge with branch
```bash
git merge BRANCH_NAME
```
### to delete a branch
```bash
git branch -d BRANCH_NAME
```
### to clone a project
```bash
git clone PROJECT_URL
```
### show commit detail
```bash
git show COMMIT_HASH
```
### show git tags
```bash
git tag
```
### to tag last commit
```bash
git tag -a TAG_NAME -m 'message'
```
### to tag a specific commit
```bash
git tag -a TAG_NAME COMMIT_HASH -m 'message'
```
### show tag detail
```bash 
git show TAG_NAME
```
### to blame a file
```bash
git blame FILE.FORMAT
```
### to blame a line of a file
```bash
git blame FILE.FORMAT -LNUMER_OF_LINE
```
### to limit a blame
```bash
git blame FILE.FORMAT -LSTART_LINE_NUMBER,END_LINE_NUMBER
```