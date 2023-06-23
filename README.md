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
Before you can commit a change to a file , you need to add the file to staging area . use 'git status' to see which changed files have and have not been adde. to add all files that have been changed use :
```git add.
```
or 
```
git add -A
```
