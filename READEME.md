Git Command
----------- Github to Local system-----------

1--> clone repository (Here we cloning repo from Github)

git clone https://github.com/Abhinav12013975/LearnGit.git
where (https://github.com/Abhinav12013975/LearnGit.git) is https of github

ls command --> Give us list of file

git status --> Show change in our *****code

Type of git status
1. untracked file (U) : new file that is not track by git
2. modified (M) : it show change in our file which tracked by git.
3. staged : file is ready to be committed
4. unmodifined : unchanged

**** important
After making changes tracked or untracked before pusing it to the github we need save changes

git add . --> It add all tracked or untracked  file for staging

git commit -m "message" --> It take screenshot of changes made during add. It reflect no more changes

After add and commit...

We use push command to push our code ....
push command --> push command is used to push local repo content to remote repo

git push origin main


--------------- Local system to Git hub-----------------
Let we have local file and we want to push it on github . These are following command

1. git init --> It create new git repo

2. git add .

3. git commit -m "message"

4. git remote add origin <---https---link>

5. git branch -M main (pusing on main branch)

6. git push -u origin main 


------------ Git Branches ------------
git branch command --> git branch command show on which branch currently we are

git checkout <---branch name---> : It helps to navigate from current branch to <---branch name--->. we will provide.

git checkout -b <---new branch name---> : It is used to create new branch

git branch -d <---branch name---> : It is used to delete branch.

***Note : if we currently on same branch which we want to delete. First checkout from this branch then we can delete it. 


