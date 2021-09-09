# GitComments
Advance git comments

**Cherry Pickup - need to copy the other changes in local 
**
1. git remote add forkname <otherperson-gitlink>
2. git fetch --all
3. git cherry-pick <commitId>  Here refer the PR commit ID 

**
Just rebase and push to master on CI to take latest code to avoid check-in problem on PR**
1. git pull --rebase upstream master
2. git push -f
