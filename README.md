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

**## How to get git commit history**
```
git log
```
>_displays the commit/merge hostory in the descending order_

**##How to add/link the remote repository to the local repository**
```
git remote add origin "https://github.com/mkalkere/Git.git"
```
>_adds or links the local git repository to the remote repository. In this case local repository will be aliased as `origin` and the remote repository as `master`_

**##How to check the remote git url**
```
git remote -v 
    OR
git remote --verbose
```
>_Displays the origin name and the remote url_

Ex:
>_origin  https://github.com/mkalkere/Git.git (fetch)_

>_origin  https://github.com/mkalkere/Git.git (push)_

**##How to rename the git remote name**
```
git remote <old_name> <new_name>
git remote origin origin1
```
>_In this case the old name `origin` will be renamed to `origin1`_

**##How to remove the remote tracking**
```
git remote remove <remote_name>
git remote rm <remote_name>

git remote remove origin1
git remote rm origin1
```
>_Removes the remote tracking configuration which was named `origin1`_