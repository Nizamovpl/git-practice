Very first time you use a new computer
----------------------------

    git config --global user.name "Insert name"
    git config --global user.email "Insert professional email"

Setting up a new project (repository, folder)
----------------------------------- 
    git init

When you want to check which step you are on
-------------------------------------

    git status

Three step commit process
----------------------------------

* make saved, tested changes to my code (usually) get it completly working
* Add any changed files to the stage
    git add filename.rb
* Commit the staged files
    git commit -m "Descriptive commit message to myself and others"

How to Sync code 
------------------------------
* When starting code on a new computer, you clone the code by git clone and then the HTTL or SSN (or whatever)
* You can then use the commands git push and git pull to get source code and take it away
* always pull code when you are syncing with another computer
