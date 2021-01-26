# Github Usage

## [Official Website](https://langarastudent.herokuapp.com/)

## Table of contents
* [Git Commands](#git-commands)
* [Commit Syntax](#commit-syntax)
* [Remote Commands](#remote-commands)
* [Set Up](#set-up)
* [Update](#update)
* [Merge](#merge)
* [Conflict](#conflict)

## Git Commands
![](./screenshot/git_basic_commands.png)

## Commit Syntax
![](./screenshot/commits_syntax.png)

## Remote Commands
![](./screenshot/remote_commands.png)

## Set Up

I already "git init" the project, so you can skip "git init" and go ahead with: 

#### Option 1: As a developer ( Skip this step if you go with option 2 ) 

```
$ git clone https://github.com/Henry-Ta/Langara_Student
$ cd Langara_Student
```

#### Option 2: Open Source Software Workflow - OSS ( Skip this step if you with option 1 )

"fork" the [project](https://github.com/Henry-Ta/Langara_Student) to your own profile

and then "git clone" the "fork" version to your computer

```
$ git clone https://github.com/Henry-Ta/Langara_Student
$ cd Langara_Student
```

#### Update your github profile:

```
$ git config --global user.name "Yujeong"
$ git config --global user.email "yujeong.choung@gmail.com"
```

## Update

If use already had directory of project

```
$ git pull origin (Gets changes from remote, updates local w/c)
or
$ git fetch origin (Gets changes from remote, without updating local w/c )
```
Otherwise, clone the project

```
$ git clone https://github.com/Henry-Ta/Langara_Student
$ cd Langara_Student
```

## Merge
#### If you follow Option 1 in Set Up

If you're currently not in branch "master"

```
$ git checkout master
$ git merge --no-ff "name of current branch"   (note: --no-ff is merging not fast forward, you can use merge only in some cases not important )
$ git push origin
```

#### If you follow Option 2 in Set Up
Simply send me request to merge on github, then i'll process it

## Conflict 

Please check out conflicts and update every single of them by choosing "Use me" or "Use both" or simply leave it there and contact me to solve it
