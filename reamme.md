this is git codes
git config --global user.name ""
git config --global user.email ""
git config --list
git clone                             -->to clone repository
cd                           					-->to change directory
cd ..                        					-->to go back to previous folder
mkdir <folder name>           			  -->to create new folder
ls                           					-->to see files
ls -a                        					-->to see hidden files
clear                        					-->to clear terminal
git status                   					-->to check status
git add .                    					-->to add changes
git commit -m ""             					-->to finalize changes
git push origin main         					-->to push code to main repository
git push -u origin main      					-->to push code and in future we just use git push
git push                     					-->after we used -u then we just use git push
git init                     					-->to create new local repository
git remote add origin <link> 					-->to add repo link where we want to push
git remote -v                					-->to verify remote repo
git branch                   					-->to check which branch we are working on
git branch -M <name>         					-->to change branch name
git checkout <branch name>    				-->to move to another branch
git checkout -b <branch name> 				-->to create new branch
git branch -d <branch name>   				-->to delete branch
git diff <branch name>        				-->to check differences b/w branches
git merge <branch name>       				-->to merge 2 branches
git pull origin main         					-->to fetch changes from remote repo
git reset <file name>        					-->to reset the changes we add only if multiple file than we use git reset only
git reset HEAD~1             					-->to reset latest commit
git log                      					-->to check commits
git reset <9ce4dc013e05a9d9291f2118be39bdbcdda8c72e>            --> to reset commit to this commit
git reset --hard <9ce4dc013e05a9d9291f2118be39bdbcdda8c72e>     --> to reset commit as well as changes in vs code 
