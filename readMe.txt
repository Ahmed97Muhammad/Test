git get status = git status
git stage command for one file = git add filename
git stage command for all changed files = git add .
git remove from stage = git rm --cached filename
git commit history = git log or git log --oneline

Check , Revert , Reset commit

Check view karna
    syntax: git checkout commitno goback = git checkout master
Revert trash me dalna specefic commit
    syntax: git revert commitno for getting out shift:  then wq
Reset yaha tak ura do commit history se edit me rakhta ha
    syntax: git reset commitno rakhta ha editor me or git reset commitno --hard nhe rakhta editor me

Creating branch
    git branch bname
    git branch -a //gets all the branches of your project

Creating branch and going to it
    git checkout -b branchname

got to a specefic branch
    git checkout branchname

for deleting a branch
    git checkout master
    git branch -D branchname

Merging branches
    go to the branch you want it to be merge with
    git merge branchname


Git Hub it is now

Creating an empty repository then same steps except origin one
    git clone repositorylink

Adding a repository already made on pc
    git push githublink branchname

for not pasting the whole path use
    git remote add origin https://github.com/Ahmed97Muhammad/Test.git

now use origin instead of whole path
    git push origin master

to get latest update of the repository go to master then
    git pull origin master

adding branch then pull request then wait for others to review and finally owner merges it to master branch
