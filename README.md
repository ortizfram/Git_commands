# Git_commands

# #...How to Move inside, Create directories, commit, etc

*_  code .            **|to open file in editor**

_  rm (fileX)  **|delete file**

_ git restore (fileX)  **|restoring files deleted**

// git rm (fileX)  **|delete and commit together**

_  ls                **|to show files**

_  cd                **|to search a fil from directory**

_  cd ..             **|to go back**

-----------------------------------
# #... rename

_ mv (fileOldName) (fileNewName)  **|rename file**

// git mv (fileOldName) (fileNewName) **|rename & commit**


# #… INIT


*_  git init          **|crate .git inside directory**

---------------------------
# #... add

*_  git add      **|just first loads and,CONFIRM MODIFICATIONS of files**     

/how?  |archivo1.txt |.txt(all from class)| . (ALL THINGS)

 /if want to add more and not .| archivo1.txt (space) archivo2.txt
 
 -------------------------------
 # #... status
                  
*_  git status        **|status of repository**

*// git status -s  **|shows status w less text & simbols**

-----------------------------
# #... commit

*_  git commit -m "first commit"  **|after add**

-----------------------------

_  ls -a             **|shows directories from git**

_  cd .git           **|to enter git directory**

_  git add README.md **|to stage file, (just changes)**



_  git push         **|to upload**



git branch -M main

git remote add origin https://github.com/ortizfram/Git_commands.git

git push -u origin main


# …or push an existing repository from the command line

git remote add origin https://github.com/ortizfram/Git_commands.git

git branch -M main

git push -u origin main
