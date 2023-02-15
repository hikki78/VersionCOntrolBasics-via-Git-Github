# VersionControlBasics-via-Git-&-Github
Some Linux and GIT COMMANDS for everyday use <3 :
ls - list of all the things in your desktop folder
mkdir - make directory 
cd - change directory 
cat - for opening the files content inside the selected directory
git init - initialise a empty git repo 
ls -a - to see (<...>.git folder after making a directory and initialising git 
touch - command to start a new file 
git status - to see the status of/in the file
git add - adding things to the given git repo
git add . - adding history/track of all the files in the folder
git add FILENAME - it can be use to bring change to a certain file 
git commit -m - it commits the changes(creation/insertion/deletion) to the git repo and '-m' for a message on related to change written in between "" 
vi - making changes to the file
git stash - keeping files at stash, u can use this with the unstaged file (check it by git status command , if red then unstaged)
git stash clear - cleaning the stash
git reset - so in this one you have to use git log at first and the COPY the previous file to the one u want to get rid of and the use "git reset PASTE". 
git remote add origin <URL> - copying the github url and bringing it to the local file.
git push origin main - if u wanna push something in a master branch 
git branch NAMEOFTHENEWBRANCH - making a new branch from the main branch. 
git merge NAMEOFTHENEWBRAN - merging the new created branch to the main branch.


How to work with existing projects on lets say GITHUB?
-> SO basically we have to go to GITHUB and then FORK the project you want to work on to your own github acc
-> then, after doing that , next CLONE the project to your local system by copying the link then going to your local text editor and write "git clone PASTE_THE_URL_YOU_COPIED".
-> use "git remote add upstream PASTE_THE_URL_YOU_COPIED". So basically just like 'origin' we did just on the earlier for OUR OWN repo , upstream is being used to address the source repo from where we forked it.
-> then create a new branch "git branch NAME" and if you are willing to check out the branch then use "git checkout NAME"
-> then add the thing u want with git add . and then commit that with git commit -m "..."
-> then push the completed thing to the project. So in this process you can't be able to use "git push upstream ___" because you can't push it directly to the main project, you have to push on the forked version of your file "git push origin ____"
p.s- force push command - "git push name -f"
-> Now it is time for pull request, so what's PULL REQUEST? Basically, the person who is contributing to the main project makes a request to the owner of the main project via pull request.
-> also after making the pull request merged by the main project if you want to add the change in the main project to your forked project then you have to use "git pull upstream main" , in this way your local folder will get in sync with the main branch of the main project , now to send this to your forked branch you have to do "git push origin main"





