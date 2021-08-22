# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Package.json is a json file used to hold the manifest(metadata) which are relavent to the project, and also used for managing the project dependencies, scrips, versions, etc.

``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```

As package.json hold the dependencies related to the project. It is required for all levels of the project. If the project involves node.js, its related npm packages and any properties being set for the projects will also be part of the package.json.

```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build

```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Env file 
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```

Heroku logs(deploy, build) can be viewed under Herohu Dashboard->Activity(after login to heroku), the other way to view the run-time application logs are Command line interface.

All logs are accessiable both through dashboard/CLI.

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Heroku allows automatic deploys, which can configured(Under deployment Method-> 1- App connected to the github, 2- Automatic deploys), while setting up initial deploymentin Heroku.

```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching allows development of upcoming multiple features seperately and also to fix the bugs. 
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happenat all stages of the integration.
first right after the developer confirmed that the feature/bug fix is done. One to cross check that the code adhere to the organization defined standard and also allows the team members in knowledge transfer.
Another factor is to validate the code changes doesn't break other's code while integrating.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Git merge, which allows to merging the forked branch back into the single branch(main).

```
