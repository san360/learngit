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

# git remove files from repo
git rm "file4.txt"
git commit -am "deleted file"
git push -u origin master, Push changes to remote
git log //view log history

# git reset
git reset --hard, reset uncomiited changes

# git revert
git revert HEAD, revert to another commit, changes are tracked in git log

# move file
git mv file5.txt , Moves a file within git repo
