# Useful git ressources

## Add a branch created on remote
1. run `git fetch`
2. run `git checkout -t origin/branch-name`

## Create a remote for local repo

1. create a remote repo with the same name
2. run `git remote add origin git@github/gitlab:username/repo-name.git`
3. run `git push -u origin`