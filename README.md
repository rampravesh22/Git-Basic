
# Learn Git and Github

This is easiest way to learn basic Git


## Starting Git

Add user Name and Email.

```bash
  $ git config --global user.name "rpc"
  $ git config --global user.email "rpc737@gmail.com"

```
Edit username and email.
```bash
  $ git config --global edit

```
## Git command start.
Make folder a git repository.
```bash
  go to that folder and run the following command

  $ git init

```
Git status: This command shows all the changes in the repository
```bash
  $ git status 

```
To add file in staging area 
```bash
  $ git add file_name

  ex: file name can any type python, txt, cpp, java etc. 

```
Add all the file in the staging area at once
```bash
  $ git add .

```
To commit file in the repository
```bash
  $ git commit -m " initial : it is bascially comment " 

```
To see all the commit in the repository
```bash
  $ git log

```
To go to the different branches point
```bash
  $ git checkout branch_name

```
## Git Branch
To check all the branches
```bash
  $ git branch

```
To create new branch
```bash
  $ git branch new_branch_name

```
To switch to another branch
```bash
  $ git checkout branch_name

```
To create a new branch and move to that branch directly.
```bash
  $ git checkout -b new_branch_name

```
To merge the child branch into the parent branch
```bash
  $ git merge child_branch_name

```
    
