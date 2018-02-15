# lern

1.Config email and name for the tracking of the changes made and commite
    git config --global user.email "email id" for email
    git config --global user.name "user name" for name
2.To initialized the git or including the .git file
    git init.
3.To know the file r added or not in git use
    git status
  if files r not added then it show "untracked file"
 Every time if u add anythink in files or make any changes in files it will show untracked file 
 then we have to add file again to git . 

4.To add the file in git use
    git add file name with extension
  after this its sayes this file are add in git .

5.This is use to save the files and changes.
    git commit -m "message what changes did"
  it use like a snapshot.

6.To upload code in clud the remote for the location we it will stor 
   gir remote add origin repo link.

7.It will push the file to clud
  git puch origin master
  
8. if any new user want to use code 
   downlode and use that 
  git clone url of repo.

9.Pull is use when another master is useing the file of master than if some file are newly added than we use this
  git pull origin master

 2 user can share the file easyly 



Creating branchs 
 Branchs use when 2 differnt user are there and they working on differnt spc. of a project .
 In that case we make branch, it make the 2 copy of source code and give to different branch user.
 Means it make the main source file isolate for a instance so th. our source file will not effect.
 after complete changes it marge all the files.

 "git branch" it will show the list of branch .
 "git branch new branch name"  To add a branch .
 "git checkout new branch name" to swotch branch.
here i create a branch name as new_branch.
 "git merge new branch name" (in master ) To add 2 branch .

log
 It is use to see the history of changes of files and commites.
 "git log" to see all the commit 
 "git log -1" it show the last commit only
 "git log --oneline" it show only the messages
 "git log --grep="messages" it show according to messages
 "git log --author="username" it show changes maid according to author
 
stash
 
 It save the cordes in a temp memory and we can assess the code any time
  "git stash list" it show all stash stored file and there unique name
  "git stash save "added name" it save the stash and it removed from main file
  "git stash apply unique name" it will restore the saved data
  "git stash drop unique name" it will delete the stash.
  "git stash clean " it will delete all stash.

  "git stach -p" it use to make stash to a pertucalur state.
  

