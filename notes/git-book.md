# Notes on Pro Git
## By Scott Chacon and Ben Straub [Link](https://www.git-scm.com/book/en/v2)

### Chapter 2 - Getting Started
 - `git init` - creates a git repository from an existing directory
 - `git add` - adds a file to be tracked
 - `git commit` - commits the changes
 - `git clone` - pulls a full data copy of an existing repo
  - You can add an aditional argument to `clone` which will specifiy the directory name you want it to create
 - `git status` - allows you to see what state your files are in
  - You can add `-s` to get a short status with a simplified output
  - ?? - Means they aren't tracked
  - A - Means they are staged
  - M - Means they are modified
 - create a `.gitignore` file if you have files you don't want tracked or shown as untracked
 - `git diff` - shows you the exact differences you've made
  - Like a extra long `git status`
  - You can add `--staged` to only focus on staged files
 - You can add a `-m` to `git commit` to specify the changes inline
 - `-a` added to `git commit` allows you to skip the staging area for items that are already tracked #helpful!
 - `git rm` - removes a file from git and removes it from the working directory
  - You have to use `-f` to force the removal if the file was already in the staging area
 - `git mv` - moves a file or renames it
 - `git log` - allows you to see the history
  - `p` shows you the difference between commits
  - `-#` allows you to limit the number of entries displayed
  - `--stat` shows abbreviated stats
  - `--since=` shows entries made in a certain time frame
 - `git commit --ammend` - allows you to redo the previous commit
 - `git reset HEAD` - removes an item from the staging area
 - `git checkout -- <file>` allows you to undo your changes
 
For right now this is all I need to know. I will check back with this book as my git usage becomes more and more complex.
