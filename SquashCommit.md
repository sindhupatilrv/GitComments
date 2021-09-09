**How to Squash the commit on PR**

1. Swicth to master -> git pull upstream master
2. Switch back to current working branch -> git checkout <working-branch>
3. pull latest code on current branch -> git pull upstream master
4. git rebase master -i 
   ---here pick the line you want to commit and squash the line dont want to show on PR
5. git push -f 
  
 once it push to PR and make sure your commited message showing on PR commit section
  
