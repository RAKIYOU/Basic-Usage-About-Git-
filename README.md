# Basic Usage About Git
## About Git.
Git is currently the most popular distributed version control system to track the changes in source code in the world. It is especially important and helpful when people collaborate with each other to develop software.

### Use GIT to manage projects in remote warehouses, like Github.

(1) Download URL related project, Only for the first time.
```
git cone git@github.com:RAKIYOU/Training-GAN-on-MNIST.git
```
(2) Cd to the environment where the project is located.
```
cd /Users/apple/Desktop/Data-Augmentation-through-Transform-Class-master
```
(3) Initialize the .git file. If it already exists, you may ignore this step.
```
git init
```
(4) Check the current branch to ensure that the new operation does not occur in the master branch but in the new branch.
```
git status
```
(5) Create a new branch, and switch to it. All modifications to project are on this branch.
```
git checkout  -b new_branch
```
(6) Edit project.  

(7) Save this change.
```
git add .
```
(8) Add a commit.
```
git commit -m “any description to your operation” 
```
(9) Push the new branch to the remote Gitlab.
```
git push -u origin HEAD 
```
(10) Return to the current master branch.
```
git checkout master
```
## Note
Please find a good post [here](https://towardsdatascience.com/top-20-most-frequently-used-git-commands-part-1-5f8c9212509f) which is about some often used Git command.  
