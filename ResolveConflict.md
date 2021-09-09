**How to resolve the conflict on Git**
1. In local, go to git-> switch the branch -
      git checkout <conflict-branch>
2. copy the commit number from your conflict PR -> in local -> 
      git reset --hard <PR-commit-No>
   Now, your latest commit shows as HEAD is now at commit id COMMIT MESSGAE
3. Swicth to master -> 
      git checkout master
4. Pull latest code -> 
      git pull upstream master
5. Checkout the working branch -> 
      git checkout <conflict-branch>
6. rebase with master on conflict branch -> 
      git rebase master
7. Modify or update the changes in conflict branch 
8. Ammed the changes -> 
     git commit --amend -> save the note
9. git push -f

 **In case to edit or add a new file or modify the file**
        
1. git rebase -i head~1
2. git add filename
3. git rebase --continue
4. git push -f -no-verify 
