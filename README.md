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

**M** **|modief file**  (if green= stagged) (if red = not stagged)

**??** **|not stagged file** -->  **A** **|added file to STAGE**  

-----------------------------
# #.. diff

_  git diff  **|see all changes up to now EXIT Q**

_  git diff --staged (just greens)  **|see all changes up to now EXIT Q**

----------------------------
# #... commit

*_  git commit -m "first commit"  **|after add**

-----------------------------
# #.. log (all repository story)

_  git log --oneline  **|numero HASH de cada commit**

------------------------
# #..Branches

_  git branch **|inwhat branch am i ?**

_  git checkout -b (ticketNUmber || features/nombre_rama) **|create new branch**

