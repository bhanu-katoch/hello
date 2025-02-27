```
git clone <url>
```
## authentication of github
1. create a token from settings of github
2. just do simple ```git push```
3. enter username and token hash code as password. 
4. after authentication no need to do authentication again for ```git pull```
### ```commit -am``` 
here -am works for modified files only. If there are new files then has to be add as ```git add .``` first.
### keep both changes of merge conflicts
```
git pull --no-rebase origin main
```
### move head as per hashcode of previous version
```
 git reset --hard <hashcode>
 git push --force
 ```
 ### move head as per per origin
 ```
 git reset --hard origin/main
 ```
 ### create branch
 ```
 git checkout -b <branch name>
 ```
 ### switch branch
 ```
 git checkout <branch name>
 ```
 ### merge branch
 ```
 git merge <branch name>
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