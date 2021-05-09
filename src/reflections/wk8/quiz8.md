# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Contains metadata for dependencies, version, and scripts
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Top level of the folder
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
Npm i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
Either in the activity tab or using $ heroku logs in the activity tab
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Once changes are pushed to github use the heroku git:remote -a <YOUR PROJECT NAME> command and then use git push heroku master command to push changes to the app.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It helps when merging pushes together and when multiple developers are working on the same application
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Before changes are merged back to the master branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging, you merge changes from a branch to another by creating a pull request and merging the updated files.
```
