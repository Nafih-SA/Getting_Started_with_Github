# TEST

testing how to convert an unversioned folder to a git repository and upload it to github.

## Procedure
1. Goto the folder & Initiaize Git
```
cd <Directory>
git init
```

2. Add README.md
```
git add README.md
```
or
```
notepad README.md
```
3. Do the first commit
```
git commit -m "first commit"
```

4. Add remote repository
```
git add remote <remote_name> <repo_url/repo.git>
```
5. Push changes to remote repository
```
git push
```