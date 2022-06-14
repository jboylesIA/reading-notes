## Reading Notes - 03**

### Working With Local Files

Within GitHub there is the option to work "offline" or in a scenario where there is no network conenction or when you prefer to keep files for local editing.  The local file that is refered to as the a clone is pulled from your GitHub repo and stored local at a lcoation of choice for editing.  The work flow for saving editied files, also known as commiting still retains some of the same steps as if you were working from on the Github site although there is a few key differences that we'll review below.  

1. When a file is edited, it is flagged as *Modified* and *Staged*.
2. Next you will *Commit* the file.  A *Commit* can also be viewed as a snapshot of a file or a save.  
3. Lastly you will want to *Push* the file back to Github.

![The Life Cycle of File Status](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

#### Commands To Note:
- Committing a file: *git commit -m “made change x,y,z”*
- Committing all changes *git commit -a*
- Pushing changes to GitHub: *git push origin master*
- Checking file status: *git status*

[For additonal information please see: Comprehensive Git Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
