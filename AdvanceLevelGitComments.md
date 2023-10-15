# GitComments
Advance git comments

**Cherry Pickup - need to copy the other changes in local**
**
1. git remote add forkname <otherperson-gitlink>
2. git fetch --all
3. git cherry-pick <commitId>  Here refer the PR commit ID 

**How to avoid cache problem on CI while running Fork PR**
1. git pull --rebase upstream master
2. git push -f
