# notes

## date: Thu, Sep 21, 2017.

### aim: adding angular-universal to mjc app for pre-rendering
### steps
* installed dependencies from "https://universal.angular.io/quickstart/"
* added angular-universal middleware function in package/server/middleware and refered it in package/server/middleware.json in final object.
* installed typings to install following dependencies:  "node express body-parser serve-static express-serve-static-core mime"
* copied the code from the above link to the new middleware
* on running 'node app.js' in package/, encountered "Error: Cannot find module 'angualar2-universal"
