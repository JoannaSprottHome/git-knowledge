# git-knowledge

<p float="left">
  <img src="images/git-icon.png" width="30" />
  <img src="images/git-hub-icon.png" width="30" /> 
</p>

Practice repo for interview questions abbout git/github.

### Most Common Commands

`git init`  
`git clone`  
`git status`  
`git add .`  
`git commit -m "message"`  
`git remote add origin https://github.com/JoannaSprottHome/git-knowledge.git`  
`git push -u origin master` - first push  
`git push origin <branch-name>`  
`git pull origin master`  
`git checkout <branch-name>`  
`git checkout -b <my-new-branch>`  
`git merge origin/master`   
`git pull`  
`git branch -D <branch-to-delete>`   

### Branching strategies to investigate:

- **Feature branching**
A feature branch model keeps all of the changes for a particular feature inside of a branch. When the feature is fully tested and validated by automated tests, the branch is then merged into master.
- **Task branching**
In this model each task is implemented on its own branch with the task key included in the branch name. It is easy to see which code implements which task, just look for the task key in the branch name.
- **Release branching**
Once the develop branch has acquired enough features for a release, you can clone that branch to form a Release branch. Creating this branch starts the next release cycle, so no new features can be added after this point, only bug fixes, documentation generation, and other release-oriented tasks should go in this branch. Once it is ready to ship, the release gets merged into master and tagged with a version number. In addition, it should be merged back into develop branch, which may have progressed since the release was initiated.

#### References:
- https://www.edureka.co/blog/interview-questions/top-devops-interview-questions-2016/
- https://www.simplilearn.com/tutorials/devops-tutorial/devops-interview-questions
