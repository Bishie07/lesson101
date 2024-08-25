# lesson 101
This lesson describes how to push codes from local environment to git hub which is remote repository emphasizing physical nature of github  
## Download Git Bash  
- https://git-scm.com/downloads
## Configure Git Bash  
- git config --global user.name  "name"
- git config --global user.email  "email"
## Cofigure Environment  
- mkdir Challant
- cx Challant
- touch name.html
- git init
## Clone Your Repo
- git remote add origin url (this should be the url from your created repo-use https)
## Push to github  
- git status
- git add Bishie.html
- git commit -m "Create Bishie.html"
- git push origin master
## Convert File to github Pages  
- Navigate to the settings tab of your repo 
- From the general session locate Pages
- From the deployment and build session > Select the Branch document > click save
- Wait for one or more mins, refresh the page to retreive the github page for the file
