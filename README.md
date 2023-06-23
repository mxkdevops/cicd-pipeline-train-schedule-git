# cicd-pipeline-train-schedule-git

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.

## Running the app

It is not necessary to run this app locally in order to complete the learning activities, but if you wish to do so you will need a local installation of npm. Begin by installing the npm dependencies with:

    npm install

Then, you can run the app with:

    npm start

Once it is running, you can access it in a browser at [http://localhost:3000](http://localhost:3000)

# Steps need to know 
clone , add , commit , push , Branch , merge , pull request

Install git 
```
sudo yum -y install git
```

```
   git --version
```
# After installation configure your name and email
```
git config --global user.name "<your name>"
git config --global user.email "<your email>"
```
some basic Git commands are : 
```
git --version
git status
git commit
```
if you are working with source code that already exist in a remote repositry , first thing you need is do is geta copy of the rpository so that you can work with the files locally .
```
git clone <repository url>
git clone git@github.com:mxkdevops/cicd-pipeline-train-schedule-git.git
```
The add commad stages changed files for the next commit . This allows you to control which files are commited and which are not 
```
git add <file>
```
Before you can commit a change to a file , you need to add the file to staging area . use `git status` to see which changed files have and have not been adde. to add all files that have been changed use :
```
git add.
```
or 
```
git add -A
```
`Commit adds` your changes to your local repository and makes them part of the repository change history. when you are satisfied witha change or set of changes that you have made to the files , you are ready to commit them :
```
git commit -m "<messages describing the change >"
```
Few notes to commit :
* Commit only adds the changes to your local copy of the repository . It does not push them to any remote repository . such as GitHub
* Commit will only commit the changes that were staged using `git add `

By default push will push the changes to a remote repository assocaited with the current local brunch. if you clone the branch from an exisiting remote repository , this relationship is already set up for you .
```
git push -u "<remote name , usually origin>"<branch anme>
```
Edit the view -index file change the header text 
```
git status
git add .
git status
git commit -m "Header text changes"
```
Now push changes to remote repositry 
```
git push
```
Git pull commmand merge their change other team review the change  
```
git pull
```
Git checkout command check the branch and create a new branch if i use -b 
```
git checkout -b new-branch name
git checkout -b new-branch
```
Now if you go back to master branch 
```
git checkout master
```
Create tag 
```
git tag myTag
```

