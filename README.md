##GIT CHEAT SHEET

git log						#log for project
git log file				#log for given file

git diff file				#changes to given file

git state					#Show what is on stage, what files are changed and not on stage

git add file				#Adds file to stage

git rm file					#removes file

git commit -m "Message"		#Commits files that has been staged
git commit 					#Opens editor for longer than one-line comment for commit

git show hash-fragment		#shows details of given hash
git show HEAD~1				#shows details of one before last commit

git annotate file			#shows summary with commits for given file

git diff HEAD..HEAD~2		#show difference between two commits, this case last commit and third from last commit

git config --list --system	#list configurations for all users (whole system)
git config --list --global	#list configurations for all projects (for a given user)
git config --list --local	#list configurations for given project

git config --global user.email dryguz@gmail.com		#change global setting for user email to dryguz@gmail.com

git checkout -- file		#clears the file to the last staged version
git checkout branch			#switch branch (requires committed changes) 
git reset HEAD file			#unstage the file

git checkout -b branch_name	#creating new branch and moving to it

git init repo_name			#create a new repo

git clone url://address destination			#clone a repo from address to destination, 
											#if destination is omitted than takes name of repo for folder

git remote add remote_name url://address 			#add remote connection to repo with remote_name
git remote rm remote_name							#remove a remote connection

git pull origin master		#pulls and merge everything in branch master or the remote origin

git puch origin master		#pushes committed changes to branch master in remote origin
 
git merge test				#merges differences from test to current branch
