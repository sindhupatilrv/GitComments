# Git Basics 

**#1. How to clone or pull code into Local**
1. Go to a local directory using git bash 
2. git clone <clone-link> folder name
	the folder name is required
3. add your fork to the main master branch - > git remote add upstream <link>
4. check by using git remote -vv 
	
**#2.	How to push code to git repository 1st time**
1. git init -> to initiate the git in the local repository
2. git add . / git add files/folder name
3. git commit -m "Message"
4. git push -u origin master / git push -f 

**#3.To create a new branch **
1. git checkout -b <Newbranchname>

**#4 To list all the branch**
1. git branch 

**#5. To switch to another branch**
1. git checkout <branchName>

**#6. How to pull or fetch**
1. git pull 
2. git fetch

**How to amend the old commit**
1. Do the changes locally if required
2. git add. / git add <filename>
3. git commit --amend
4. Then it will open the vi editor window, later make sure your last commit,
