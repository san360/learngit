# learngit
# Simple add, commit and ammend an existing commit
git add .
git commit -am "commit message"
git commit --amend -m "commit message"

# git un staged file
vim file4.txt
git add .
git status // Check the status
git rm --cached file4.txt  //removes the file from local index, i.e. unstage a file
git status // Check the status