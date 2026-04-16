git init
    - intializes an empty git repository 

git status
    - git status will give you information what branch you use and how many commits you have made how many track and untracked

Branch :
    you ever you are doing git init you create a master branch or you also called as main branch 


git checkout -b dev:-
    create a new branch and switch to dev branch

git add file_name

git commit -m "-m : message"

commit 
    - if you want to save a file or add a file


git restore file_name
    - to restore the the deleted file 

git restore --stage <file_name> 
    - used to untrack/unstage the staged file


add command -
    stage
commit command - 
    tracked


git log

git reverts <log - 4a84c8895b4f17e953a87f9d66a80b7e0b1a9f2e>


git --help

git branch -> give the list of all the branch of git repo.





-----------------------------------------------

git init - intialize an empty repository
git status - check the status of the vcs
git add - to add untrack to stage
git commit - to commit stage to tracked
git restore - deleted file to restore
git rm - to stage to untrack


git status                                                      
   git restore --stage .\hii.py  
  
  git add .                                                       
  14 git status                                                      
  15 git commit -m                                                   
  16 git commit -m "message"                                         
  17 git status                                                      
  18 git status                                                      
  19 git commit -m "message"                                         
  20 git add .                                                       
  21 git commit -m "hello"                                           
                                                      
  27 git restore .\hii.py                                            
  36 git status                                                      
  37 git commit -m "message"                                         
  38 git status                                                      
  39 git --version                                         

  43 python .\testing.py                                             
                                                             
  48 git init                                                        
  49 git status                                                      
  50 git checkout master                                             
  60 git add .\testing.py                                            
  61 git status                                                      
  62 git restore --stage .\testing.py                                
  63 git rm --cached .\testing.py                                    
  64 git status                                                      
  65 git status                                                      
  66 git add .\hee.txt                                               
  67 git status                                                      
  68 cls                                                             
  69 git status                                                      
  70 git add .                                                       
  71 git status                                                      
   git commit -m "add new file"                                    
  
   git restore hee.txt                                             
   git commit -m "added new file"                                  
  82 git status                                                      
  83 cls                                                             
  84 git status                                                      
  85 git checkout main                                               
  86 git checkout master                                             
git rm --cached hii.txt                                         
git restore --stage .\hii.txt                                   
       
                                                       
  git rm --cached hii.txt                                         

 git     add .                                              
 
git restore --stage hii.txt                                     




=====================================
git remote add origiin <url>
git remote -v
git remote set-url origin <PAC token>
git push origin main


git add -a

