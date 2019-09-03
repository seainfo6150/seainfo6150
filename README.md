# INFO6150
Class syllabus and class notes can be found in the `docs` directory in this repo.
Repository of notes and in-class example files.

# Github guide
We will use github repos throughout the course. If you are not familiar with git, or could use a refresher on how to use git, this is an excellent starter guide: https://guides.github.com/activities/hello-world/

# Forking class repo and setting upstream remote
1. Make sure you have git installed: https://git-scm.com/downloads
2. Go to the git repo for this class: https://github.com/aprilbingham-neu/seainfo6150
3. Click “Fork” to create your copy of the repo
4. Click “Clone or download” to get a link to copy your fork on your computer
5. Click “Use HTTPS”
6. Copy link
7. Open command line/terminal window and use these commands in a directory where you have admin permissions
```
git clone [copied link]
cd seainfo6150
git remote add upstream https://github.com/aprilbingham-neu/seainfo6150
```

# Creating a branch from master
```
cd seainfo6150
git checkout master
git pull origin master
git checkout --b [new branch name]
```

# Creating a branch from a branch other than master
```
cd seainfo6150
git checkout [branch to create branch from]
git checkout --b [new branch name]
```

# Pushing your changes to your fork
Make changes to your branch, then
```
git add .
git commit -m “[commit name]”
git push origin [branch name]
```

# Pulling updates from main repo
```
cd seainfo6150
git pull upstream master
```
