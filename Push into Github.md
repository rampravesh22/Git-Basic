# Push into Github form local directory


- git push -u origin master or main is used for pushing local content to GitHub
- main or master are branch name.
- you can use another bracnh name if you want to push it into another branch


```
    git push -u origin main
  ```
   
- If ``git push -u origin master `` will not work or give error like follwing.
- error: src refspec master does not match any
- error: failed to push some refs to 'https://github.com/rickwarty/new-test.git'
- Then we have to force push to commit
```
    git push -f origin main
  ```

