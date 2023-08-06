# Github_Homework 2
## 1. In your local repository, make branches for:
- Postman   
- Jmeter   
- Checklists   
- Bug Reports   
- SQL   
- Charles   
- Mobile Testing
-    
`To make branches on the local repository, you need to create a remote repository and clone it to the local computer`   
creating a remote repo called `git_branch`   
copying HTML link `https://github.com/VSenakosau/git_branch.git` to the remote repo     
cloning this repo to the local directory `git clone https://github.com/VSenakosau/git_branch.git`

To create branches, we use the `git branch` command. Let's execute the creation of all branches in one line using `&&`

`git branch Postman && git branch Jmeter && git branch Checklists && git branch Bug_Reports && git branch SQL && git branch Charles && git branch Mobile_Testing`   

Use the `git branch` command to verify that the branches have been created
```
vvsen@Vadim MINGW64 /c/vadim/qa/github/git_branch (main)
$ git branch
  Bug_Reports
  Charles
  Checklists
  Jmeter
  Mobile_Testing
  Postman
  SQL
* main
```
## 2. Push all the branches to the remote repository.
vvsen@Vadim MINGW64 /c/vadim/qa/github/git_branch (main)   
`git push origin --all`
```
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/VSenakosau/git_branch.git
 * [new branch]      Bug_Reports -> Bug_Reports
 * [new branch]      Charles -> Charles
 * [new branch]      Checklists -> Checklists
 * [new branch]      Jmeter -> Jmeter
 * [new branch]      Mobile_Testing -> Mobile_Testing
 * [new branch]      Postman -> Postman
 * [new branch]      SQL -> SQL
```
By using the `-u` flag (--set-upstream) when pushing your branches, Git remembers the remote tracking branches for you. This makes it easier to work with remote branches in the future because you don't need to remember or specify the remote and branch names each time you pull or push changes.   
vvsen@Vadim MINGW64 /c/vadim/qa/github/git_branch (main)   
`git push -u origin --all`
```
Everything up-to-date
branch 'Bug_Reports' set up to track 'origin/Bug_Reports'.
branch 'Charles' set up to track 'origin/Charles'.
branch 'Checklists' set up to track 'origin/Checklists'.
branch 'Jmeter' set up to track 'origin/Jmeter'.
branch 'Mobile_Testing' set up to track 'origin/Mobile_Testing'.
branch 'Postman' set up to track 'origin/Postman'.
branch 'SQL' set up to track 'origin/SQL'.
branch 'main' set up to track 'origin/main'.
```
## 3. In Bug_Reports branch, create a text document with the structure of the bug report.
vvsen@Vadim MINGW64 /c/vadim/qa/github/git_branch (main)   
`git checkout Bug_Reports`
Switched to branch 'Bug_Reports'   
Your branch is up to date with 'origin/Bug_Reports'   

vvsen@Vadim MINGW64 /c/vadim/qa/github/git_branch (Bug_Reports)      
`touch br_structure.txt`

vvsen@Vadim MINGW64 /c/vadim/qa/github/git_branch (Bug_Reports)   
`nano br_structure.txt`   
Add information   
ctrl+O -> Enter (Save)      
ctrl+X -> Exit (Exit)   





