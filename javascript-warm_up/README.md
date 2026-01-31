# JavaScript - Warm Up ☕

## Project Description

This project introduces the fundamentals of JavaScript programming. It covers basic concepts such as variables, constants, data types, control structures, functions, and more.

## Learning Objectives

By the end of this project, you should be able to explain:

- Why JavaScript programming is amazing
- How to run a JavaScript script
- How to create variables and constants
- Differences between `var`, `const`, and `let`
- All the data types available in JavaScript
- How to use `if`, `if...else` statements
- How to use comments
- How to assign values to variables
- How to use `while` and `for` loops
- How to use `break` and `continue` statements
- What is a function and how to use functions
- What a function without a return statement returns
- Scope of variables
- Arithmetic operators and how to use them
- How to manipulate dictionaries (objects)
- How to import a file

## Requirements

### General
- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted on Ubuntu 20.04 LTS using Node.js (version 14.x)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/node`
- Code must be `semistandard` compliant (version 16.x.x)
- All files must be executable
- File length will be tested using `wc`

## Installation

### Install Node 14
```bash
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs
```

### Install semi-standard
```bash
sudo npm install semistandard --global
```

## Usage

To run any JavaScript file:
```bash
node filename.js
```

Or make it executable and run directly:
```bash
chmod +x filename.js
./filename.js
```

## Tasks

### 0. First constant, first print
**File:** `0-javascript_is_amazing.js`

Write a script that prints "JavaScript is amazing":
- Create a constant variable called `myVar` with the value "JavaScript is amazing"
- Use `console.log(...)` to print output
- Not allowed to use `var`

**Example:**
```bash
./0-javascript_is_amazing.js
JavaScript is amazing
```

## Code Style

This project follows the `semistandard` style guide:
- Rules of Standard + semicolons on top
- Reference: [AirBnB style](https://github.com/airbnb/javascript)

To check your code:
```bash
semistandard filename.js
```

## Technologies

- **Language:** JavaScript (ES6)
- **Runtime:** Node.js 14.x
- **Code Style:** semistandard

## Project Structure

```
javascript-warm_up/
├── .gitignore
├── README.md
├── instractions.txt
└── 0-javascript_is_amazing.js
```

## Resources

- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [JavaScript.info](https://javascript.info/)
- [Node.js Documentation](https://nodejs.org/docs/latest-v14.x/api/)
- [Semistandard Style Guide](https://github.com/standard/semistandard)

## Author

**Abdullah Alsalem**
- GitHub: [@ABDULLAHALSALEM](https://github.com/ABDULLAHALSALEM)
- Repository: [holbertonschool-web_front_end](https://github.com/ABDULLAHALSALEM/holbertonschool-web_front_end)

## Repository

- **GitHub repository:** `holbertonschool-web_front_end`
- **Directory:** `javascript-warm_up`

## Project Status

🚀 In Progress - Building JavaScript fundamentals

---

**Holberton School** - Web Front End Development
