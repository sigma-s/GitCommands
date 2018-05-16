# GitCommands
A list of commonly used git commands and resources

## Move android studio project to an already created Github Repository (only having Readme.md file)

`git remote add origin [//your github url]`

//pull those changes<br>
`git pull origin master --allow-unrelated-histories`

//now, push your work to your new repo<br>
`git push origin master`

## Add android studio project to an empt github repo
Go to root folder.<br>
`git init`<br>
`git add .`<br>
Create .gitignore txt file in root folder. Place these content in file.<br>

*.iml<br>
.gradle<br>
/local.properties<br>
/.idea/workspace.xml<br>
/.idea/libraries<br>
.idea<br>
.DS_Store<br>
/build<br>
/captures<br>
.externalNativeBuild<br>

`git remote add origin https://github.com/username/project.git`<br>

`git commit - m "My First Commit"`<br>
`git push origin`<br>

## Check the current url for remote

`git remote get-url --all origin`
