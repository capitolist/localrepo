# aayush-cp
this is aayush soni this is my first git depository
Create a GitDemo named folder make a file name & open folder in vscode
click on bottom left icon with cross and triangle to open the terminal
1-- clone command
   git clone <link>
   go to github to to code(green botton) copy the https clone link
   go to terminal type git clone https....paste link by ctrl+v
   the github depository will be cloned !!
2-- change directory 
   used to go out and in of folders
   type cd aayush-cp enter and we are inside aaysuh-cp
3-- list command
   to list all the files inside aayush-cp
   type ls 
4-- status command
    diplay the staus of code
    upto date nothing to commit means github and vscode code is same
    now edit in vscode  and type git status 
    output will be modified : README.md
5-- Untracked file 
    new file which git does know about means any changes in this file git will not known
    make a file index.html inside aayush-cp file 
    type <p>hello world</p>
    README.md ko modified and index.html ko untracked 
6-- modified 
    changed
7-- staged 
   means file is ready uton be commited 
   if changes made write add command and files are staged
   then type write commit to make status unchanged ki sab change ka screen shot ho chka hai
8-- add 
add new or changed files in your working directory to git staged area 
git add <-filename->
type git add index.html enter if  green hogya staus means staged hogya
type git add .   all files will be added in single go 
9-- commit
it is record of change 
type git commit -m "some message" 
but till now chanegs will not be done in github
10-- push command 
upload local repo content to remote repo
type git push origin main   enter output now changes done in github refresh it to see
origin means remote github repo name is origin
11-- cd .. 
to come out of a directory
12-- init command 
   we are at GitDemo now to make new directory named LocalRepo  type mkdir LocalRepo
  then type cd LocalRepo to come inside LocalRepo directory
  type git init enter then type git init enter now Localrepo is  git dipository
inside localrepo file create a index.html and style.css file
type git status output will be untracked files
type git add .   now files are added
type git status o/p changes to be commited for given files
type git commit -m "add initial files" now files added 
to upload projec tin github go to github profile your depositories new green optionmake a repo called localrepo click create repo 
type git remote add origin <-link->
copy link of local repo enter now origin is set 
type git remote -v enter to verify remote  op will be name of repo
type git branch    to check which branch we are at
type git push -u origin main  now code will be pushed in repo 
create a new file in localrepo called README.md 
write   # this is my localrepo 
type git add . 
type git commit -m "add remote" enter
type git push enter  refresh and README.md file will be visible in github
13-- work flow 
    github repo -> clone -> changes ->add ->commmit - > push
14-- git branches 
   ek developer ko dusre ka wait nhi karna padta 
15-- branch commmad
   git branch   to check branch
   git branch -M main   to rename branch
   git checkout <-branch name->  to navigate 
   git checkout -b <-new branch name->   to create new branch 






















    Author - Aayush Kumar Soni
