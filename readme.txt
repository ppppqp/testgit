This is a tutorial for git on linux.
1. To create a respository
	First, create the directory in desired location.
	Then, use commandline command (cd) to enter the directory.
	Finally, use (git init) to turn the directory into a respository.

2. To upload the file to Github:
	First, use command (git add filename) to add the file to a stage.
	Second, use command (git commit -m (your comment here)) to push all the files in the buffer zone to the cloud.
	Third, use command (git diff filename) to see what changes have been made.

3. To clone a repository from the cloud
	use command (git clone (your github url here))

4. To push your file to Github
	use command (git push origin master)

5. To pull files from Github
	use command (git pull)

6. To use SSH rather than http to access the remote repository
	First, create an ssh using command (ssh-keygen -t rsa –C “youremail@example.com”)
	Second, add the ssh(public) to your github account.
	Third, copy the ssh of your github repository
	Finally, use command (git clone SHH_of_repository) eg. git clone @github.com:blablabla
	Or, if you have already used http as a way of access, you can change it with the command (git remote add origin SHH_of_repository) and command (git push --set-upstream origin master) 


Yeah.
