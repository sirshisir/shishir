git -- help (to find command used in GitHub)
git clone <-link given in git code-> (to copy link from GitHub)
git status (to see the changes happen in code)
ls  (find the location of the file)
cd (change directory)
mkdir (make new directory)

git add filename (only file add)
git add. (i.e "." means all)(all files, changes,..)
get commit -m "Add Initial Files"
get push origin main (it shows)

Initializing directory
get int (Initialized directory)
git add filename (only file add)
git add. (i.e "." means all)(all files, changes,..)
get commit -m "Add Initial Files"
get push origin main (it shows)

git remote add origin<-link->
get remote -v (to verify remote)
get branch  (to check branch)
get branch -m main (to change or rename branch name)

get branch  (to check branch)
get branch -m main (to change or rename branch name)
git checkout -b <-new branch name->(to create a new branch)
get checkout  <- branch name->(to navigate)
get checkout -d <-branch name->(to delete  branch)

merging code
way 1:
git diff <-branch name->  (to compare commits,  branches,  files and more)
git merge <-branch name->  (to merge 2 branches)

way 2:
create a PR (done in GitHub)

pull command 
git pull origin main (used to fetch and download content from a remote repo)

undoing changes
case1:staged changes
- git reset <-filename->
- git reset

case2:commited changes(for one commit)
- git reset HEAD ~1

case3:commited change (for many comments)
- git reset <-commit hash->
- get reset --hard<-commit hash->
