# 0x01. ES6 Promises
### JavaScript ES6
 
# Resources
- Read or watch:
- Promise
- JavaScript Promise: An introduction
- Await
- Async
-Throw / Try
- Learning Objectives
- At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

# Promises (how, why, and what)
- How to use the then, resolve, catch methods
- How to use every method of the Promise object
- Throw / Try
- The await operator
- How to use an async function

# Requirements
- All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the js extension
- Your code will be tested using Jest and the command npm run test
- Your code will be verified against lint using ESLint
- All of your functions must be exported

# Setup
Install NodeJS 12.11.x
(in your home directory):

-curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
- sudo bash nodesource_setup.sh
- sudo apt install nodejs -y
- $ nodejs -v
- v12.11.1
- $ npm -v
- 6.11.3
- Install Jest, Babel, and ESLint
- in your project directory, install Jest, Babel and ESList by using the supplied package.json and run npm install.


# Tasks
0. Keep every promise you make and only make promises you can keep
Return a Promise using this prototype function getResponseFromAPI()
 
1. Don't make a promise...if you know you can't keep it
Using the prototype below, return a promise. The parameter is a boolean.

2. Catch me if you can!
mandatory

3. Handle multiple successful promises
In this file, import uploadPhoto and createUser from utils.js
  
4. Simple promise
  
5. Reject the promises
Write and export a function named uploadPhoto. It should accept one argument fileName (string).
  
6. Handle multiple promises
Import signUpUser from 4-user-promise.js and uploadPhoto from 5-photo-reject.js.
  
7. Load balancer
Write and export a function named loadBalancer. It should accept two arguments chinaDownload (Promise) and USDownload (Promise).

8. Throw error / try catch
Write a function named divideFunction that will accept two arguments: numerator (Number) and denominator (Number).

9. Throw an error

10. Await / Async
Import uploadPhoto and createUser from utils.js
