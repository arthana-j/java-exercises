NOTE : DON’T CREATE NEW BRANCH FROM THE SUB BRANCHES, CREATE NEW BRANCH USING THE main BRANCH.

git checkout <branch_name> - to switch to an existing branch

git checkout -b <branch_name> - to switch to a branch by creating a new branch

git status - to check the status of the branch

git add . - to add all files
git add <filename> - to add a specific file 

git commit -m “<message>” -  to commit the changes

git push - to push the changes , if worked on existing branch

git push -u origin <created_branch_name> - to push the changes if the branch is created using
                                           git checkout -b <branch_name>. 
                                           NOTE : ONLY USED ONCE FOR THE FIRST PUSH, THEN TREATED AS EXISTING BRANCH


Happy Coding!!
