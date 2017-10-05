### Git commands - Quick Reference

**1. Initialize `git` in a folder**
  ```
  git init
 
  ```

  > _initializes the git in the specified folder_

**2. Get the `git status`**
```
git status
```
>_gets the status of the git. specifies if there a any pending changes etc_

**3.Traking files in Git / Adding Files to Staging**
```
git add file1.txt        
```
>_Adds file1.text to Staging or starts tracking file1.txt_
```
git add *.txt
```
>_Adds/Starts tracking all .txt file_
```
git add --all
```
>_Adds/Starts tracking all the files irrespective of file types_

**4.Commit files to local git repository**
```
git commit -m "Add comment here"
```
>_commits the files tracked/added to the statging to the local repository_

