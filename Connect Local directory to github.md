
# How To Connect Local Directory To Github
- ## Open the folder in git bash or any other terminal like powershell, Command
```bash
   like this :/e/Github/todo
```

- ## Now init the currect folder by using following command
```bash
   git init
```

- ## After initializing the directory now add all the file into staging area so git can track these file like updation, deletion etc
- ### this will add all the file at once

```bash
   git add .

```
- ## After adding all the file into staging area now we have to commit so git can save all the changes
```bash
   git commit -m "Messasge"

```

## Now create a repositry in Github 
#### And you will see a message like  
#### 1-.or push an existing repository from the command line / 
### 2-…or push an existing repository from the command line

- #### After commiting run all the follwing command one by one to connect your local directory to github
- #### https://github.com/rickwarty/Todo.git it is url of repository



 ```bash
   git remote add origin https://github.com/rickwarty/Todo.git
```

	

 ```bash
   git branch -M main
```

 ```bash
   git branch -M main
```