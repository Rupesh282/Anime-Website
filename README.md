# Anime-Website
To create an Social Media platform for anime nerds !

## Getting Started : 
- Fork this repository into your profile.
![Fork](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)

- Clone it on local machine.
```
git clone <your repository's url>
```
- Set this repository as upstream.
```
git remote add upstream https://github.com/ParitoshGavali/Anime-Website.git
```
- Check the status of origin and upstream.
```
git remote -v
```
> Help, I can't understand this origin/upstream BS!! :dizzy_face:
>> - origin refers to the GitHub repository you cloned from.
>> - upstream refers to the other GitHub repository you want to pull or push changes to.
>> - So, after entring the above command you should see forked git repo in origin and this git repo in upstream.

>**_PRO TIP_ :sunglasses: ** : origin is set automatically by git but the upstream is just a convention used by almost all git users, so you can use any name instead of upstream.

> Now you are ready to code :star_struck: \
> Just kidding! :disappointed: \
> Read the next topic and then I promise that you will be ready to start (or maybe not :stuck_out_tongue_winking_eye:)
  
  ## How to collaborate : 
  
  - before making any change make sure that your are using the latest version of the branch
  - for this , first fetch the changes from upstream and them merge whichever upstream branch you want to merge with your branch
  - command for fetching from upstream :
  ```
   git fetch upstream
  ```
  - now for merging :
  ```
   git merge <your_branch_name> upstream/<branch_you_want_to_merge_with> 
  ```
  - Now You can start working on your feature
  - After completing feature / correcting spelling mistake , you have to first push the changes to origin i.e. your remote fork. for this , 
  ```
   git push
  ```
  - Now you can go to your git repo (remote fork) and create a pull request
  
  >**_PRO TIP_ :sunglasses: ** : for checking the PR (pull request) created by others , you can check it in your local machine by following command
  ```
    git fetch upstream pull/<PR NO>/head : <branch_name_you_like>
  ```
   this will create a branch in your local machine with name <branch_name_you_like>.Now checkout to this branch and do your stuff.
   
   > Some more commands : 
   - To check the status of files (tracked / untracked)
    ``` git status ```
    
   - To check the current branch
    ``` git branch ```
    
   - To switch to different branch , say branch B
    ``` git checkout B ```
    
   - To delete a branch locally (first switch to branch you don't want to delete)
    ``` git branch -d <branch_name_you_want_to_delete> ```
    
