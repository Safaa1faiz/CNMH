# Lab_Github

# work to be done. 
1. create multiple branches
2. create a conflict
3. merge the branches into the main
4. solve the conflict
   
### Steps to make conflict
After collaborate with someone else to work on some repo
### First you need clone to your repo
```
git clone https://github.com/Safaa1faiz/Lab_Github
```
### Than you need to clone your repo
- Than you can start changing in files according to your tasks => but sometimes you may change same line that your group mate changed too in this stuation when you try to merge your branch with his branch you will get a conflict.

## Create your branch and push 
 ```
git checkout -b <branch-name>
```
Replace with the desired name for your new branch. This command creates a new branch and switches to it.
If you want to create the branch but stay on your current branch, you can omit the -b flag:

 ```
git branch -b <branch-name>
```
## After creating the branch, you can switch to it later using:
  ```
git checkout <branch-name>
```
Or, if you're using Git version 2.23 or later, you can use the git switch command to switch branches:

  ```
git switch <branch-name>
```
Remember to replace with the actual name you want to give to your new branch.
 ## To merge branches barnch-1 and branch-2 into the main branch, follow these steps:

 ### Ensure You're on the Main Branch:

Before you start merging, ensure that you are on the main branch. You can switch to the main branch using the following command:

  ```
git checkout main
```
## Pull the Latest Changes:
### It's a good practice to ensure your main branch is up-to-date with the remote repository before merging any branches. You can do this with:

  ```
git pull origin main
```

## Merge the Branches: 
To merge the barnch-1 into main, use the following command:
  ```
git merge barnch-1
```
Then, if there are no conflicts, to merge the branch-2 into main, use:
  ```
git merge barnch-2
```
## Resolve Conflicts (If Any):
If there are conflicts during the merge process, Git will pause and allow you to resolve them. You'll need to open the conflicted files, resolve the conflicts

### Follow this steps to resolve conflict:

  ```
<body>
    <p>
       branch2 Lorem ipsum dolor sit amet consectetur, 
        adipisicing elit. Illum dignissimos, 
        quibusdam asperiores nihil vel quis aliquid qui,
         ratione iusto tenetur ipsa omnis voluptatum? Ullam eum maiores 
         molestiae cum animi libero?
    </p>
    
</body>
```

### Accept Current Change
use it if you want to keep the current change ignore the Incoming Change

### Accept Incoming Change
use it if you want to keep the Incoming Change ignore the current Change
### Accept Both Changes
use it if you want to keep the both Changes
### Compare Changes
use it if you want to caompare changes and see what you want to keep and what you want to change

## Then stage the resolved files using:
 ```
git add <conflicted-file-name>
```
Once all conflicts are resolved, continue the merge process with:
 ```
git merge --continue
```
## Commit the Merged Changes: 
After resolving any conflicts and making sure everything is as you want it, commit the merged changes:
 ```
git commit -m "Merge branch-1 and branch-2 into main"
```
### Push the Changes to Remote:

Finally, push the merged changes to the remote repository:
```
git push origin main
```
Now, the changes from the bracnh-1 and branch-2 branches are merged into the main branch. Make sure to thoroughly test the merged code to ensure everything is working as expected before pushing to production if applicable.

