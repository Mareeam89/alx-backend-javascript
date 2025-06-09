## Project Description
Learn how to use NodeJS modules.
How to use specific Node JS module to read files.
How to use `process` to access command line arguments and the environment.
How to create a small HTTP server using Node JS.
How to create a small HTTP server using Express JS.
How to create advanced routes with Express JS.
How to use ES6 with Node JS with Babel-node.
How to use Nodemon to develop faster.

## More Info
### Install Node 18
```
$ curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

### Install Jest, Babel, and ESLint
```
$ npm install --save-dev jest
$ npm install --save-dev babel-jest @babel/core @babel/preset-env
$ npm install --save-dev eslint
```

**Find the configuration files `package.json`, `babel.config.js` and `.eslintrc.js` in the project directory. Run `npm install` when you have the `package.json`**


* **0. Executing basic javascript with Node JS** - Create a function named `displayMessage` that prints in `STDOUT` the string argument. - `0-console.js`.
* **1. Using Process stdin** - Create a program `1-stdin.js` that will be executed through command line. - `1-stdin.js`.
* **2. Reading a file synchronously with Node JS** - Using the database `database.csv` (provided in project description), create a function `countStudents` in the file `2-read_file.js`. - `2-read_file.js`.
* **3. Reduce** - Using the database `database.csv` (provided in project description), create a function `countStudents`. - `3-read_file_async.js`.
* **4. Create a small HTTP server using Node's HTTP module** - Create a small HTTP server using the `http` module. - `4-http.js`.
* **5. Create a more complex HTTP server using Node's HTTP module** - Create a small HTTP server using the `http` module. - `5-http.js`.
* **6. Create a small HTTP server using Express** - Install Express create a small HTTP server using Express module. - `6-http_express.js`.
* **7. Create a more complex HTTP server using Express** - Recreate the small HTTP server using Express. - `7-http_express.js`.

