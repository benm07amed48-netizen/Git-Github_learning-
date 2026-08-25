# Git-Github\_learning-

this repo is for learning GIT \& GITHUB

### Github Commands :

- git clone    		 	====    to transfer the repo to your local
- git push origin main   	====    to upload the projects to the remote repo
- git remote add origin &lt;link&gt;  ====    to link the local repo with remote repo
- git push -u origin master    	====    to pull before uploading


### Git Commands :
- git init    		        ====    to create new repo
- git add &lt;file name&gt;     	====    to add file(s) to the index repo index
- git commit -m "comment"   	====    to commit change including explanation messages 
- git mv &lt;file name&gt;   	        ====    to change file name from index and local dir
- git rm &lt;file name&gt;   	        ====    to remove a file from both index and local dir 
- git rm --cache &lt;file name&gt;   	====    to remove only from staging area 
- git restore --staged &lt;file&gt;  	====    to unstage the last satges consider file not changed from last commit
- git status    	        ====    to see the diffrences between local index object store
- git diff     		        ====    to check the differences between local & index 
- git diff --cashed     	====    to check the differences between index & last commit 
- git branch    	        ====    to show the branches on your local git repo
- git branch &lt;branh name&gt;    	====    to create 
- git checkout &lt;branch name&gt; 	====	to swith to the branch
- git branch -d &lt;branch name&gt;	====	to delete the branch ~ safe ~
- git branch -D &lt;branch name&gt;	====	to delete the branch ~ force ~
- git checkout -b &lt;branch name&gt;	====	to create and swith to the branch 
- git branch -m &lt;new name&gt;	====	to rename the branch you are in 
- git stash 		        ====	to add index files to stash
- git stash save "stash name"	====	to add index files to stash named ~ stash name ~
- git stash list 	        ====	to show the stashes you have 
- git stash pop/apply &lt;stash&gt;	====	to get the stash items to your index with/out removing the stash &lt;stash&gt;
- git stash show &lt;stash&gt;	====	to show the stash content 
- git stash drop &lt;stash&gt; 	====	to remove the stash &lt;stash&gt;
- git clean -n 			====	to show the untracked files about to be deleted  
- git clean -f 			====	to delete the untracked files  
- git reset head --hard &lt;hash&gt;	====	to reverse time to the after selected commit use force pushing after
- git reset head --soft &lt;hash&gt;	====	to cancel commits and send file to staging area  use force pushing after
- git add -f &lt;file name&gt;	====	to add the ignored file 
- git tag &lt;release n°/name&gt;	==== 	to detect tag without comment it's the snapshot
- git tag -a &lt;name&gt; -m "msg"	==== 	to detect tag and adding comment   


- git config --global alias.&lt;shortcut&gt; "&lt;command to be shortcuted&gt;"  