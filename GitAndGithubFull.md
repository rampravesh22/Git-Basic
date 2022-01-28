# Git and Github full 

- ## ` git init `  
  ### command : to iniialize the folder into git
  - it is use to initialize the folder as git so the git can track the history 
  - first go to that folder and run the following command
```bash
     git init
```
- ## `ls -a `  
  ### command : show the hidden folder list
  - it is use to see the hidden file and folder
  - 
```bash
     ls -a
```

- ## `touch new_file.ext`  
  ### command: To creat a new file 
  - it is use to create a new file
  - touch file_name.extension ( extesnion can be any type like .py .txt .cpp .java .md etc)
```bash
     touch new_file.ext
```

- ## ` To create a new username and email` 
  ### command : To see all the file and folder

  $ git config --global user.name "rpc"
  $ git config --global user.email "rpc737@gmail.com"

- ## ` To edit a new username and email` 
```bash
  $ git config --global edit

```


- ## ` git init `  command : to iniialize the folder into git
  - it is use to initialize the folder as git so the git can track the history 
  - first go to that folder and run the following command
```bash
     git init
```

- ## ` git status`  
  ### command : To see the change in git repo
  -  It is basically use to see the all the cahnges that are made in the git repository
  - 
```bash
     git status
```

- ## `git add  filename`  
  ### command : To add the file in tracking area
  -  When we run this command is make the file into the tracking area where the git can track the history
  - Without running this command git can not track the history of the file that has neen modiefied
  - By this command we can stage only one file into tracking area
```bash
     git add filename.ext
```

- ## `git add .`  
  ### command : To stage all the file into tracking area
  -  This command add all the file into the staging area
```bash
     git add .
```
- ## `git restore --staged file_name.ext`
###  command : To stage the file from trackin area
  -  This command remove all the file from staging area into unstage 
  - file name can be like a.md, a.py, a.txt etc.
```bash
     git restore --unstage file_name
```

- ## `git commit -m "a.txt file added` 
  ### command : To commit all the changes
  -  It is use to commit or save all the chnages that has been made into file
  - `-m` means to provide a message while comminting the file 
```bash
     git commit -m "Message while commiting"
```


- ## `git log`  
  ### command : It shows entire commited history
  - To see the history of the all the modification and commited 
```bash
     git log
```


- ## `git reset hash_code` 
  ### command : To go back to any specific commit
  - It is use to reset the commit or go back to previous commit
  - Hash code : get it from the ``git log'``
```bash
     git reset hash_code
```

- ## `git stash` 
  ### command : Means saving it in directory without committing it 
  - By running this command it saves the file in directory without recording it in git repository
  - But whenever we need this file we can bring it back
```bash
     git stash
```
- ## `git stash pop` 
  ### command : To return all the file in the staging area who area saved without committing it
  - It bring back all the file into staging area the file that has been saved in the directory without committing the file 
```bash
     git stash pop
```

- ## `git stash clear` 
  ### command : To remove all the file that are back staged without committed  
```bash
     git stash clear
```

# Attach the local git directory to github repository

- ## `git remote add origin urls` 
  ### command : It is use to attach your local directory to github repository
  - urls: this url is generates when we create a new respository on github
  - example - https://github.com/rickwarty/Git-Basic.git

```bash
     git remote add origin urls
```

- ## `git push origin master` 
  ### command : After attaching the github with the local directory please run the push command to see the all file inside the folder
  -  git push command is to push all the file on the github repository
  -  
```bash
     git push origin master
```

- ## `To make contribution in open source` 
  ### command : Fork that project in your account 
  - After fork, clone this project into your local directory
  
  - ## `git clone url_of_repository` 
  ### command : It cloned the repo into the local directory
   
```bash
     git clone url_of_repository
```


- ## `git push origin new_branch -f` 
  ### command : 
  -  
  -  
```bash
     git log (To find the hash code of the commit)

     git reset hash_code

     git psuh origin new_branch -f
     (now we have to forced push because some of the commit has deleted but online repository have some extra commit)
```


# Git Branch
- ## To check all the branches
```bash
   git branch

```
- ## To create new branch
```bash
   git branch new_branch_name

```
- ## To switch to another branch
```bash
   git checkout branch_name

```
- ## To create a new branch and move to that branch directly.
```bash
   git checkout -b new_branch_name

```
- ## To merge the child branch into the parent branch
```bash
   git merge child_branch_name

```


