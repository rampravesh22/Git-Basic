
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
-  goto the parent branch that you want to merge and then run the follwing command with child branch name
```bash
   git merge child_branch_name
```


- ## To Rebase the alternate branch in the main branch
-  checkout to the experiment or alternate branch `git checkout experiment` 
   ```bash
   git checkout experiment
   ```

   ![basic-rebase-1](https://user-images.githubusercontent.com/82926209/151645967-4523d3f0-6e44-4602-8aba-b915b25368d6.png)
   
   
 - now rebase the branch into the main/master
   ```bash
   git rebase master

   ```
   ![basic-rebase-3](https://user-images.githubusercontent.com/82926209/151646102-a5dc9c15-df67-4c2d-9b6d-a6febe98869c.png)
- At this point, you can go back to the master branch and do a fast-forward merge.

   ```bash
    git checkout master
    git merge experiment
   ```
![basic-rebase-4](https://user-images.githubusercontent.com/82926209/151646131-55b53aa2-f76e-4871-8162-355a16b7e4a4.png)

