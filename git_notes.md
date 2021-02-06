#Notes on How to setup git and sync with Github

[Useful notes from Colt Steele](https://www.notion.so/Introduction-to-Git-ac396a0697704709a12b6a0e545db049#5b7377e4b75a4a32bfe992c47b3697e7)
[Colt Steele Video introduction to Git](https://www.youtube.com/watch?v=USjZcfj8yxE)
###Install Git
- sudo apt-get install git

###Setup username and email
- git config --global user.name "Your Name"
- git config --global user.email "your@email.com"

###Initialise Repository
- git init

###Commands for working with git
- git add some_file -  add a file to a repository
- git add . - add all file to a repository
- git status - check status of repository
- git commit -m "Commit Message"
- git log - show the logs for each commit
- git checkout <commit hash> - Go back to the commit with specified hash
- git checkout master - return to master branch

- .gitignore - make a file called .gitignore and list files you want git to ignore in here [would you like to know more?](https://help.github.com/en/articles/ignoring-files)

###Branches
- git branch <new_branch_name> - Make a new branch
- git branch - List branches
*git makes a temporary branc when you are working on a file.*

- git merge <branch_name_to_merge> - merge the branch specified to the master branch.
 
