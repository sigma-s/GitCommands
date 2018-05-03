# GitCommands
A list of commonly used git commands and resources

##Move android studio project to an already created Github Repository (only having Readme.md file)

`git remote add origin [//your github url]`

//pull those changes
`git pull origin master --allow-unrelated-histories`

//now, push your work to your new repo
`git push origin master`

##Add android studio project to an empt github repo
Go to root folder.
`git init`
`git add .`
Create .gitignore txt file in root folder. Place these content in file.

*.iml
.gradle
/local.properties
/.idea/workspace.xml
/.idea/libraries
.idea
.DS_Store
/build
/captures
.externalNativeBuild

`git remote add origin https://github.com/username/project.git`

`git commit - m "My First Commit"`
`git push origin`
