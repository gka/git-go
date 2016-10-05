# git-go

*git-go* is a short-hand command for doing 

```
git add -A
git add -u
git commit -m "SOME MESSAGE"
git pull
git push
```

It is a dangerous practice, but it saves a lot of time. Also it encourages [committing early and often](http://www.databasically.com/2011/03/14/git-commit-early-commit-often/).

### Usage

It's really just `git-go COMMITMSG`. Note that you don't have to put quotes around the commit message.

```
git-go your commit message goes here
```

If you intend to use quotes, you need to escape them using `\`.

```
git-go I\'m done coding
```

### Installation

```
npm install -g git-go
```

### Credit

This is just a nodejs port of @jashkenas' git-go Ruby script.
