# Git Basics - important steps for git workflow

Initialize a new repository with git init
Create changes to project files in the text editor
check status of those files with git status
stage changes for commits by command: git add (file name) 
          or with a (.) to add all the file changes
commit changes to version history with command: 
          git commit -m "Insert a brief message about the change made here"
review previous changes with git log (press q when ready to exit git log)
You can see the specific changes made to a file before commiting by using git diff

And if you need to remove a repository that has hidden and/or regular files in it, 
          use command: rm -rf repository-name

if you want to add a branch, use command: git branch name_of_new_branch 
to switch between branches, use command git checkout name_of_branch_you_want_to_switch_to 
if you want to delete a branch, use command: git branch -d name_of_branch 
          (hint: you cant be in that branch when trying to delete it)