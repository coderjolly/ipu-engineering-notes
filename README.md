# Welcome to IPU-Engineering-Notes

Our open source community helps in gathering notes for students studying in GGSIPU, or whenever someone gets trapped, they can refer to the notes. 
So, we are developing a repository and trying to implementat it for all semesters .
## Steps to follow :scroll:

### 1. Fork it :fork_and_knife:
You can get your own fork/copy of [IPU-Engineering-Notes](https://github.com/CoderJolly/IPU-Engineering-Notes) by using the <a href="https://github.com/CoderJolly/IPU_Engineering_Material/new/master?readme=1#fork-destination-box"><kbd><b>Fork</b></kbd></a> button or clicking [this](https://github.com/CoderJolly/IPU-Engineering-Notes/new/master?readme=1#fork-destination-box).
 [![Fork Button](https://help.github.com/assets/images/help/repository/fork_button.jpg)](https://github.com/CoderJolly/IPU-Engineering-Notes)
 
 
### 2. Clone it :busts_in_silhouette:
You need to clone (download) it to local machine using
```sh
$ git clone https://github.com/Your_Username/IPU-Engineering-Notes.git
```
> This makes a local copy of repository in your machine.
Once you have cloned the `IPU-Engineering-Notes` repository in Github, move to that folder first using change directory command on linux and Mac.
```sh
# This will change directory to a folder IPU-Engineering-Notes
$ cd IPU-Engineering-Notes
```
Move to this folder for all other commands.

### 3. Set it up :arrow_up:
Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:
```sh
$ git remote -v
origin  https://github.com/Your_Username/IPU-Engineering-Notes.git (fetch)
origin  https://github.com/Your_Username/IPU-Engineering-Notes.git (push)
```
Now, lets add a reference to the original [IPU-Engineering-Notes](https://github.com/Coderjolly/IPU_Engineering_Material) repository using
```sh
$ git remote add upstream https://github.com/Coderjolly/IPU-Engineering-Notes.git
```
> This adds a new remote named ***upstream***.
See the changes using
```sh
$ git remote -v
origin    https://github.com/Your_Username/IPU-Engineering-Notes.git (fetch)
origin    https://github.com/Your_Username/IPU-Engineering-Notes.git (push)
upstream  https://github.com/Coderjolly/IPU-Engineering-Notes.git (fetch)
upstream  https://github.com/Coderjolly/IPU-Engineering-Notes.git (push)
```

### 4. Ready Steady Go... :turtle: :rabbit2:
Once you have completed these steps, you are ready to start contributing by checking our `Help Wanted` Issues and creating [pull requests](https://github.com/Coderjolly/IPU-Engineering-Notes.git/pulls).

### 5. Create a new branch :bangbang:
Whenever you are going to make contribution. Please create separate branch using command and keep your `master` branch clean (i.e. synced with remote branch).
```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b Folder_Name
```
Create a separate branch for contribution and try to use same name of branch as of folder.
To switch to desired branch
```sh
# To switch from one folder to other
$ git checkout Folder_Name
```
To add the changes to the branch. Use
```sh
# To add all files to branch Folder_Name
$ git add .
```
Type in a message relevant for the code reviewer using
```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```
Now, Push your awesome work to your remote repository using
```sh
# To push your work to your remote repository
$ git push -u origin Folder_Name
```
Finally, go to your repository in browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious effort.**

