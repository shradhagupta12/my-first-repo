# my-first-repo
Practice account for learning GIT 

# 1 . How to clone repo to your desktop ?
  a. copy the http link of the repo. open the cdm in desktop.
  b. make a directory.
  c. get into directory.
  d. right the command : git clone https://github.com/shradhagupta12/my-first-repo.git .
  e. you have clone your repo successfully.

# 2. Commit repo ? 
  a. touch test.txt //made a txt file
  b. git add test.txt
  c. git commit -m "Adding a new file for testing"
  d. git config --global user.email "user.gmail.com"
  e. git config --global user.name "Shraddha"
  f. git status 
  g. git commit -m "Adding a new file for testing"
  e. git status
  Hence commited successfully.

# How to make a branch using terminal for the given repo
  a. Check first if any repo is pending in repo command : git status.
  b. git checkout -B feature/lesson.
  c. git branch.
  d. touch test2.txt.
  e. git add test2.txt.
  f. git commit -m "Add test2.txt in branch repo".
  g. git push -u origin feature/lesson.
  h. git status.
  i. go to github website and check the repo.
  j. popup will appear with a pull request. 
  k. commit the pull request.
  Hence branch with successfull pull request has been submitted.

# Git Blame
  a. By using 'git blame [file name]' you get the you get details of changes till date.
  b. You can also get specific data by filtering the change list 'git blame -L 3,8 [File name]' --(-L = list for blame change list , 3 and 8 in which get the details       
      between 3 and 8 index number).
  c. Fomat of deatils [ID][Authour Name][Date and Time][Index Number][Changes made].
  d. 'git log -p [ID]' will give the indepth details of changes made.
  
