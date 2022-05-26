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
  **crate .git inside directory**
```
git init        
```
---------------------------
# #... ADD
**first loads and,CONFIRM MODIFICATIONS of files**   
```
git add        
```
**How?** ⬇ 

|archivo1.txt 

|.txt(all from class)

:star: ( . ALL THINGS)
```
git add .
```

 /if want to add more and not (. ALL)
 ```
 archivo1.txt (space) archivo2.txt
 ```
 -------------------------------
 # #... status
 **status of repository**
```                  
git status        
```
 **shows status with less text & simbols**
```
git status -s 
```
**M** **=modief file** ---> (if 🟢 = **stagged**) ---> (if 🔴 = not stagged)

**??🔴** **=nt stagged** -->  **A🟢** **=added file to STAGE**  

-----------------------------
# #.. diff
**|see all changes up to now EXIT Q**
```
git diff  
```
(just 🟢)  **|see all changes up to now EXIT Q**
```
git diff --staged 
```
----------------------------
# #... COMMIT
 :star: **|after add**
```
git commit -m "first commit" 
```
-----------------------------
# #.. log (all repository story)
**|HASH number for every commit**
```
git log --oneline  
```
------------------------
# #..Branches, moving beweenB & Merge
**|inwhat branch am i ?**
```
git branch 
```
**|create new branch**
```
git checkout -b (ticketNUmber(not obligatory)  BranchName) 
```
**|change branch**
```
- git checkout (branchName)  
```
 **|moving code thats valid to main branch**
```
git merge (branchName_that_wanna_bring_to_main/master)
```
-------------------------
# #..cat (see what is inside)
```
git (fileName.txt)
```
----------------------------
# #..upload to :cloud: GITHUB

1. create a repository manually

2. `git init` (when folder located in terminal)

3. `git add .` , or git add (fileName) 

4. `git commit -m "adding files"`

5. `git remote add origin https://github.com/yourusername/your-repo-name.git`push the changes to your Git repository hosted with

   GitHub.

*Note: your-repo-name should be created in GitHub before you do a git remote add origin ...

6. `git push -u origin master`


