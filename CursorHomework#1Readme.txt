1. Create a new repository on GitHub.
2. Open Git Bash.
3. cd e:/Java_Old/Java_IntelliJ_IDEA/CURSOR/1    //go to the folder where the files will be stored
4. touch CursorHomework#1.txt  //create file CursorHomework#1.txt main file for work
5. touch CursorHomework#1Readme.txt  //create file CursorHomework#1Readme.txt file where step by step commands are described
6. git init //initialize the local directory as a Git repository.
7. git add .  //add all files that are created in the folder
8. git status   //check what is in the folder. Should reflect 2 file creation
9. git commit -m "add file touchCursorHomework#1 and file CursorHomework#1Readme"  //we give the name a change. Save changes before sending to repository
10. git remote add origin https://github.com/Falcon89/CHW-1.git  //URL address of the created repository
11. git push -u origin master   //publish change to repository
10. git checkout -b new-branche   //creating a new branch like 'new-branche' after creation, we automatically move to a new branch.
11. git add .  //adding all file with which we are working on a change.
12. git commit -m "Changes file CursorHomework#1 and CursorHomework#1Readme"  //we give the name a change. Save changes before sending to repository
13. git push -u origin new-branche   //publish change to repository in branch 'new-branche'
14. git checkout master //switch to the master branch
15. git merge new-branche   //git merge with history commit 'new-branche'
16. git push   ////publish change to repository master branch