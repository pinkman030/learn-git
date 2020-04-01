#Git Tutorials by ian schoonover

-what is Git?
	git is version control system which stores reference point to snapshots of your code
	this creates linear timeline of your work/project
	
#States in Git
1. working directory
	an area where all our files and directories and changes are living all the time
2. staging area
	files and directories that we add explicitly add to staging area 
3. repository
	where all our snapshots are stored to review/check in future.
	
#Commands in Git
1. git init
2. git status
3. git add
4. git commit
5. git log




#Adding multiple files of certain type
	git add *.<file extension> - eg.git add *.html

#Adding all files in directory (including hidden)
	git add -A
	
#Removing files 
	git reset HEAD <file> - git reset HEAD delete.txt 
	
#Ignoring files
	 1.create .gitignore file 
	 2. write a name of the files that you want to ignore in ".gitignore" file 





# Git Branches

- listing all branches
		git branch
		
- adding a branch
	git checkout -b <branch name>	eg. git checkout -b feature1

- changing a branches
		git checkout <branch name>
		
- merging a branch
		git merge <branch name>		eg. git merge feature1
	

- removing a branch
		git branch -d <branch name> eg. git branch -d feature1
	
 
		0---0----0
       /		 /
      /			/	
0-----0---0-----0


useful links-
https://medium.com/@devsprout/how-to-connect-goormide-to-github-with-ssh-67a293bf3cb0



#Git and Github creating new repository
-create a new repository on the command line
echo "# dummy" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/pinkman030/<repository name>.git
git push -u origin master

-push an existing repository from the command line
git remote add origin https://github.com/pinkman030/<repository name>.git
git push -u origin master




