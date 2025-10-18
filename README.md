# Git (Version Control System)
## Git Install for Ubuntu
```
sudo apt update
sudo apt-get install git
git --version
git config --global user.name "xxx"
git config --global user.email "xxx@example.com"
```

## Working with GitHub projects
### Create the repository, clone it to Ubuntu working directory
1. Create a new repository in GitHub
2. Clone local copy of the repository
```
cd [NAME OF REPOSITORY]
git clone [HTTPS ADDRESS]
```
3. 4 steps in a commit: ‘status’ , ‘add’ , ‘commit’ and ‘push’
```
git status
git add [FILENAME] [FILENAME] [...]
git commit -m "Add comment"
git remote
git push origin master
```
