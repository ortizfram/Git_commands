# Git_commands
how to move inside, create directories, commit, etc

# …or create a new repository on the command line

echo "# Git_commands" >> README.md
git init        #crate .git inside directory 
ls -a           ##shows directories from git
cd .git         ##to enter git directory
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ortizfram/Git_commands.git
git push -u origin main


# …or push an existing repository from the command line

git remote add origin https://github.com/ortizfram/Git_commands.git
git branch -M main
git push -u origin main
