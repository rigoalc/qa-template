# qa-template

## Purpose
##### short sentence about what is broken

## Artifacts
##### screenshots of the problem

## Steps to Reproduce
##### how many clicks or actions it took you to find the problem

### steps to start environment
```bash
$ cd projects
$ git clone {git repository https address (found by clicking the green CODE button on a Github repository website)}
$ cd {name of git repository and the folder that you just created}
$ code . <- open Visual Studio Code Editor to the folder that you 
// MAKE CHANGE TO CODE
$ git add .
$ git commit -m "{your message}"
$ git push origin master <- branch like a tree
$ git checkout -b {branch-name} <- CREATES a new branch
// MAKE CHANGES TO CODE
$ git add .
$ git commit -m "{your message}"
$ git push origin {branch-name}
$ git checkout master
```

GIT