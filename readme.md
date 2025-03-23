- ```https://github.com/new``` to add new repo quickly
- ```git clone <url>``` to clone repo
## authentication of github
1. create a token from settings of github
2. just do simple ```git push```
3. enter username and token hash code as password. 
4. after authentication no need to do authentication again for ```git pull```
## need of commit and add
- ```git add``` is used to tell the git which files has to be kept in track and ```git commit``` is used to tell the git to save **snapshot** of version of file.

### ```commit -am``` 
- Here -am works for modified files only that are staged at all yet. If there are new files then has to be add( staged yet ) then do as ```git add .``` ***first***.    

- ```.``` means to add all files of **repo** otherwise for specific files use ```git add <filename>```.

## Merge Conflicts
### keep both changes of merge conflicts
- use ```git pull --no-rebase origin main``` as simple ```git pull``` doesn't bring editing of changes of conflict in editor maye be in some os it is.
- use ```git pull``` since whatever is the case we are bringing it to our pc for negotiating changes so don't confuse what to do in case of ```git push```
## reset
### move head as per hashcode of previous version
```
 git reset --hard <hashcode>
 git push --force
 ```
 ### move head as per per origin
 ```
 git reset --hard origin/main
 ```
 ## branch
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
 ### push branch to github
 ```
 git push origin <branch name>
 ``` 
### for safely delete ensuring delete if merged
```
git branch -d <branch-name>
```
### for force delete branch
```
git branch -D <branch-name>
```
### to delete branchfrom github
```
git push origin --delete <branch-name>
```
