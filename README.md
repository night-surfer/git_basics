# Git Basics - important steps for git workflow


#### Steps for commiting changes to files

# Initialize (or create) a new repository with git init

# Create changes to project files in the text editor

# check status of those files withthe command: git status

#stage changes for commits by command: git add file_name 
          or with a (.) to add all the file changes

#commit changes to version history with command: 
          git commit -m "Insert a brief message about the change made here"

#review previous changes with git log (press q when ready to exit git log)

#You can see the specific changes made to a file before commiting it by using: git diff


###### Removing a repository

#And if you need to remove a repository that has hidden and/or regular files in it, 
          use command: rm -rf repository-name


####### Branches

#if you want to add a branch, use command: git branch name_of_new_branch 

#to switch between branches, use command git checkout name_of_branch_you_want_to_switch_to 

#if you want to delete a branch, use command: git branch -d name_of_branch 
          (hint: you cant be in that branch when trying to delete it)
          
          
##### Push to github 

#Go to github.com and make new repository there

#clone or copy: git remote add url_given_to copy

#enter: git branch -M main

#enter: git push -u origin main

#enter: username and PAT token when promted

#then check: git log to see changes. Then check github.com for updates