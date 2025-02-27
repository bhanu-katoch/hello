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