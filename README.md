# ls -a
- To See the file and folder in this folder.
# git init     
- Initialized empty Git repository in /Users/rohit.singh1/Desktop/React JS Learning/Gitdemo/.git/
# git add .    
- to add All untracket file.
# git commit -m"message for commit" 
- For Commiting the code with commit message
# git remote add origin <link>
- remote - Here "remote" is (Git Platform where repository is available )
- "add origin" is for we want to commit by the origin.
- "link" link is here the path of repository.
# git remote -v   
- It tell us what is the remote 
- origin  https://github.com/rohit9454-fire/GITDEMO.git (fetch)
- origin  https://github.com/rohit9454-fire/GITDEMO.git (push)
# git branch
- To check current branch
# git branch -M branchName
- To Change the branch name.
# git push origin branchName
- To push the file on remote repo
# git push -u origin main
- Here "u" is set the default branch for the push, It means We Don't write again and again whole santance can push my code using only 
- "git push" but the branch is always "main"
# git checkout <-branchName->
- Navigate One Branch to another Branch.
# git checkout -b <-branchName->
- To Create A New Branch.   
# git branch -d <-branchName->
- To Delete the branch. *NOTE* We can not delete the branch if I'm on The Same Brach which i want to delete.

Example: 
rohit.singh1@Indigos-MacBook-Pro-3 Gitdemo % git branch               
  dev
* dev_rohit
  main
If I try to delete "dev_rohit" branch so we get the ERROR: error: Cannot delete branch 'dev_rohit' checked out at '/Users/rohit.singh1/Desktop/React JS Learning/Gitdemo'


