Hi Ho! My name is README.md

I am on branch sample

Adding a line on master

## Adding a title for next commit
```
[//]: # (Merging parent in current branch)
git checkout anothersample
git fetch origin master
git merge origin master
git status
[//]: # (There could be merge conflicts, fix them manually)
git commit -a -m "merged master; fixed"
git push origin anothersample

[//]: # (Pull request accept or merging child branch in itself)
git checkout master
git merge anothersample
git status
git push origin master
```
