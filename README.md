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
## 2. Push all the branches to the remote repository
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
