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







