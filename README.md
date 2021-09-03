# GitPraticeBasicMaster1

Git init to initiate the git command in local repo
Create repo in github
and Link both with remote git

Command :
git init
git add . 
git status 
git commit -m "message" 
git remote add origin <gir url>
git push -u origin master
git log
git reset commitID
git reset/restor Head 
git rm -d path
git log --oneline
git diff

To Create New Branch and Update to the Global Repo: 

	  git branch new branch 
	  git push origin my_new_branch (it will take the master update and push the changes to new branch ) - using orphan only branch will be empty (else git rm -r to remove for empty   branch)
	 
To Switch the Branch and Merge the other Branch 

	  git checkout branchName (switch the branch)
	  git merge branchtomerge(branch name)
      
To Switch the master and Merge the other Branch 

	  navigate to master dir
	  git push origin branchtomerge(branch name)
  
And if you want the updated commits of Branch1 on Branch2, you are probaly looking for git rebase

	git checkout Branch2
	git rebase Branch1
  
Clone the Master to Branch : To clone this in local and make sure the repo name not in the local and to update thr branch also do the same clone
  
  git clone -b GitPraticeBasicBranch3 https://github.com/mrgsathyaraj/GitPraticeBasicMaster1.git
  
  git push origin branchname
  
  raise an  pull request from branch and this will be received to the master for merge/commit or rebase/commit
  
  branch pull request will be changed from open to  merged
  
git branch-a to see the available local and remote branches

Compare two branches :

  git diff branch_1...branch_2
  
Compare master and branch :

  git diff master...branch
  
You can git branch -a to list all branches (local and remote) and then choose the branch name from the list (just remove remotes/ from the remote branch name.

Example: git diff main origin/main (where "main" is the local main branch and "origin/main" is a remote, namely the origin and main branch.)
  
===========================================================================================================================================================
  



