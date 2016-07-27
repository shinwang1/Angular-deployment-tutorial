# Angular-deployment-tutorial
macOS, Yeoman, AngularJS 1.x, Grunt, Github, Heroku

**Purpose:** The purpose for writing this post is to share what I have learned over the three days (through trial and error) about using [Grunt](http://gruntjs.com). I hope that it’ll get you up and running within the hour. I will also be editing to this article as I learn more from the community and documentations.

**Context:** My team and I had seven days to learn enough about a new framework to build our final project at [Dev Bootcamp](http://devbootcamp.com), a coding bootcamp. We decided to use an AngularJS front-end that connected to our Rails API back-end. While it was easy to deploy our Rails API to Heroku, we were unsuccessful at deploying our front-end. Since we used [Yeoman](http://yeoman.io/) to scaffold our Angular template, the Yeoman system included Grunt. Grunt is essentially a task runner that automates tasks that you would do repeatedly. Since we had little time to learn about how Grunt worked, we did not successfully deploy our Web App to Heroku at the time. Since then, our Web App, UpLift, has been deployed to both Github pages and Heroku. The lesson that we learned is to deploy early and often. Here are the steps that I’ve compiled since that project. Think of this as building an Angular template Web App from scratch.

## Setup and steps on macOS:

I will use the **$** to represent the mac terminal prompt.

1. Install Node.js to your system by downloading [NodeJS](https://nodejs.org/en)
2. To check if you already have a version of node:
```
$ node -v
```
