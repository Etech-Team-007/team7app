#!/bin/bash 
#Make sure you're in the main branch 

$ git checkout main

#Clone your repo if you don't have the repository

$ git clone <repo_url>

#If you have the repository already, do

$ git pull 

#Create and move into a new branch 

$ git checkout -b branch_name

#Make the necessary contributions, then do 

$ git add .

$ git commit -m "Descriptive commit message"

$ git push --set-upstream origin branch_name

#Go to GitHub and create a pull request and assign it to at least 2 senior Engineers.
