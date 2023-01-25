# Git Assignment 
# Branching Development Model

![image](https://user-images.githubusercontent.com/123532043/214673672-3f38e927-8598-4a78-af33-7447e4eda9ad.png)
<p align = "center">
Fig.1 - Final result of Repository
</p>
#### main commands

- git clone <SSH Key> => For remote connect.
- git add <filename> => to move into staging area
- git commit -m "message" => to commit changes
- git log --oneline --graph --decorate --all => to view logs
- git checkout -b <branch name> => to create branch
- git checkout <branch name> => to move into branch
- git merge <branch name> => to marge branch
- git pull <origin> <branch> => to pull changes from origin
- git 
Initially, I created git repo and added 2 reviewers.
  
#### Steps
1. After creating Github repo using SSH key cloned it locally. Now we are in main(production) branch. Now we created Hotfix and Integration branch
2. Then two branches named feature1 and feature2 are created integrate to the integration branch.
3. some changes are commited in the feature2 branch and from github pull request is created with 2 reviewers added. Branch is deleted at last.
4. some changes are commited in the feature1 branch. By using "git pull -rebase" command we rebase it. 
5. Now pull request is created with 2 reviewers same as above. Then to update these branches  Integration branch into Hotfix and Production branch are merged.
6. Now changes are commited in feature1 branch and again pull request is created with 2 reviewers. Then feature1 is merged with into Integration, Hotfix, and Production branch. this branch is deleted at last.
7. Now changes are commited in the Hotfix branch and Pull Request is created with 2 reviewers, Hotfix is merged it into the Production as well as the Integration branch
8. Feature1, Feature2, and HotFix branches were deleted after completing developing model.
