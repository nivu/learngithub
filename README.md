# Learn Github

## Version Control Systems
- SVN
- Mercurial
- Git

## Git-based source code repository hosting services
- Github
- Bitbucket
- Gitlab
- Google repositories

# Steps

### Create github account

### Create a github repo

1. Create with files (if you dont have a project dir)
2. Create without files (u you have a local project dir)

### Props of github repo

1. repo
2. url
    - https://github.com/nivukite/learngithub (share)
    - https://github.com/nivukite/learngithub.git (point to a repo)
    - git@github.com:nivukite/learngithub.git

3. braches [main]
> main -> production -> develop
> main -> newfeature

**Code | Issues | PR | Actions (CI/CD) | Project**

### Install git software
> Git GUI/ Git Bash

Commands
```
git --help
```
Make a local copy of your repo
HTTPS -> everytime u need to enter the password
```
git clone https://github.com/nivukite/learngithub.git
git branch
git checkout <branch_name>
> Ex: git checkout main
git pull
```

Add files and make changes to code
```
git staus
git add . (all all changes [file change, new file]
git add <file_name>
> Ex: git add main.txt
git commit -m "Added new file prod.txt"
git push

```
Create a pull request [code merge]

1. Create PR using github pltform

### Initialize a existing project repo

```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nivukite/gitwofiles.git
git push -u origin main
```

### Other Features

- Git fork
- Managing git merge confilcts
- Git stash

```
git stash
git stash list
git stash apply

```


#### Task

- Fork this repo
- Create a new file rollno_name_gollege_year_dept.txt
- 42_nivu_cas_2_ece.txt
- Raise PR to the master repo


