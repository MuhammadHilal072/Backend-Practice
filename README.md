# Backend Practice

Node.js and Express practice from my web development journey.

## What's inside

| Folder         | Contents |
| `node-basics/` | Core Node.js practice: modules (`math.js`, `script.js`), a `fruits/` folder used as a module (`apple.js`, `banana.js`, `orange.js`, `index.js`), and small npm-package projects (`FigletDir`, `MyProject`, `random_words`) |
| `express-get-post/` | An Express app that handles GET and POST requests (`index.js`) |

## Topics covered
- Node.js modules: `require`, `module.exports`, and using a folder as a module
- Using npm packages
- Command-line arguments with `process.argv`
- Express basics: GET and POST routes, reading `req.query` and `req.body`

## Tech
Node.js, Express, npm

## How to run
Each folder has its own dependencies.

**Express app:**

    cd express-get-post
    npm install
    node index.js

Then open http://localhost:8080.

**Node basics:**

    cd node-basics
    npm install
    node script.js

`script.js` has loop and command-line arguments (`process.argv`) examples. Most lines are commented out, so uncomment the part you want to try.

## Author
Muhammad Hilal