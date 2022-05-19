# Git_commands  :arrow_up: 🔧 📈 


# #...How to Move inside, Create directories, commit, etc

# #OPEN

**to OPEN file in editor**

```
code .
```
----------------------------------------------------
# #...DELETE

 **delete file**
 
 ```
  rm (fileX) 
```


:star: **DELETE and commit together**
```
git rm (fileX)  
```
**RESTORE files deleted**

```
git restore (fileX)  
```
----------------------------------------------------
# #...MOVE inside directory

**to show files**

1. Windows
2. Mac / IOS
```
dir
ls                
```
  **go to directory**
```
cd
```
 **to go back**
```
 cd ..            
```
-----------------------------------
# #... rename
**rename file**
```
 mv (fileOldName) (fileNewName)  
```
:star: **rename & commit**
```
git mv (fileOldName) (fileNewName) 
```
----------------------------------
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

- git checkout (branchName)  **|change branch**

- git merge (branchName_that_wanna_bring_to_main/master) **|moving code thats valid to main branch/..**

-------------------------
# #..cat (see what is inside)

_  git (fileName.txt)

----------------------------
# #..upload to cloud GITHUB

_  create a repository manually

-  git branch -M main

_  git remote add origin (**link followed by.git**) https://github.com/ortizfram/miweb.git

-  git remote set-url origin (**link followed by.git**)

![image](https://user-images.githubusercontent.com/51888893/168284554-dda1efad-4d32-449b-8863-e9fe5ed8227b.png)




_  git push -u origin master (or main) **|upload changes from working branch**



