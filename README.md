# CourseMLOps

1. how to commit in local to a particular issue (e.g. #1) on GitHub

```
by git commit -m "#1"
```

## braches

1. create a branch in your local computer
```
git branch branch-name # create a local branch
git checkout branch-name # switch to the new branch
```
2. push the new branch created local to remote
```
git push --set-upstream upstream branch-name
```

3. merge the new branch into the MASTER branch
```
git checkout master # switch back to master
git merge --no-ff branch-name
```
[difference between merge and merge --no-ff](https://stackoverflow.com/questions/9069061/what-is-the-difference-between-git-merge-and-git-merge-no-ff#targetText=The%20%2D%2Dno%2Dff%20flag,point%20at%20the%20incoming%20commit.)
