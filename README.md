# Git-test
This ia an testing repository to practice different git commands with remote repository.

g1) git init
2) git add .
3) git commit -m "message"
4) git remote add origin <url>|| git remote set-url origin <url>
5) git remote -v (verifies the url)
6) git push -f origin master( we use -f to push force fulcly)
7) git remote rm <remote-name>
8) git clone <https url of the repository>  //for clonning the repository>

=================================================================================================
How to remove git node modules
1) git rm -r --cached node_modules
2) git commit -m "removed the node_modules"
3) git push origin master

===================================================================================================
Working with Branches

creating a branch
1)git branch <Branch_name>

pushing a branch to remote origin
2)git push origin <Branch_name>

deleting a local branch
1) git branch <branch_name> -d

deleting a git branch in remote origin 
1) git push origin --delete <Branch_name>

 ======================================================================================================

For importing an remote git repository 

Dont create a new folder for the project because while you are importing it comes with the folder

cmd => git clone  <https url of the repository>  //for clonning the repository> 


==========================================================================================================

** 26 feb 2022 **

1) cloning a git repository  				==>  git clone <url>
2) Creating a new local branch 				==>  git branch <new_branch_name>
3) Listing local branches 					==>  git branch
4) Listing remote branches				==>  git branch -r
5) Listing both local and remote branches		==>  git branch --all
6) switch to another branch				==>  git checkout <branch_name>  or git switch <branch_name>
7) Creating a new local branch from remote            ==>  git checkout -b <new_branch_name> <remote_branch_name>



