### commit -am 
here -am works for modified files only if new files has to be add then
```
git add .
```
first
### keep both changes of merge conflicts
git pull --no-rebase origin main

### move head as per hashcode of previous version
```
 git reset --hard <hashcode>
 git push --force
 ```
 ### move head as per per origin
 ```
 git reset --hard origin/main
 ```
 ## push branch to github
 ```
 git push origin <branch name>
 ``` 
### for safley delete ensuring delete if merged
```
git branch -d <branch-name>
```
### for force delete branch
```
git branch -D <branch-name>
```
### to delete from github
```
git push origin --delete <branch-name>
```