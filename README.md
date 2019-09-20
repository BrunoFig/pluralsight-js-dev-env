# JavaScript Development Environment

This is a generic JavaScript Development Environment from ["Building a JavaScript Development Environment" on Pluralsight](https://app.pluralsight.com/library/courses/javascript-development-environment/table-of-contents) by [Cory House](https://github.com/coryhouse), that **isn't tied** to any specific JavaScript framework. In case of doubts refer to [Cory's GitHub repository](https://github.com/coryhouse/javascript-development-environment)

## Tools Used in the Course

* Editor: [Visual Studio Code](https://code.visualstudio.com)
* Configuration: [EditorConfig](https://editorconfig.org)
* Package Management: [NPM](https://www.npmjs.com/)
* Web Server: [Express](https://expressjs.com)
* Expose Web Server: [Localtunnel](https://localtunnel.me/)
* Automation: [NPM](https://www.npmjs.com/)
* Transpiler: [Babel](https://babeljs.io)
* Bundler: [Webpack](https://webpack.js.org/)
* Linter: [ESLint](https://eslint.org)
* Testing Framework: [Mocha](https://mochajs.org/)
  * Assertion Library: [Chai](https://www.chaijs.com/)
  * Helper Library: [JSDOM](https://github.com/jsdom/jsdom)
* Continuous Integration: 
  * [Travis](https://travis-ci.org/) (Linux)
  * [AppVeyor](https://www.appveyor.com/) (Windows)
* Mock HTTP: 
  * API Schema: [JSON Schema Faker](https://json-schema-faker.js.org/)
  * Generate Data: [Faker.js](https://github.com/marak/Faker.js/), [Chance](https://chancejs.com/) & [Randexp.js](https://github.com/fent/randexp.js)
  * Serve API: [JSON Server](https://github.com/typicode/json-server)
* Error Logging: [TrackJS](https://trackjs.com/)
* Template Engine: [EJS](https://ejs.co/)
* Cloud Hosting:
  * API: [Heroku](https://www.heroku.com/)
  * UI: [Surge](https://surge.sh/)

## Get Started

1. **Install [Node 6 or newer](https://nodejs.org)**. Need to run multiple versions of Node? Use [nvm](https://github.com/creationix/nvm) or [nvm-windows](https://github.com/coreybutler/nvm-windows)
2. **Clone this repository.**
3. **Make sure you're in the directory you just created.** - `cd pluralsight-js-dev-env`
4. **Install Node Packages.** - `npm install`
5. **Run the app.** - `npm start -s`
   This will run the automated build process, start up a webserver, and open the application in your default browser. When doing development with this kit, this command will continue watching files all your files. Every time you hit save the code is rebuilt, linting runs, and tests run automatically. Note: The -s flag is optional. It enables silent mode which suppresses unnecessary messages during the build
