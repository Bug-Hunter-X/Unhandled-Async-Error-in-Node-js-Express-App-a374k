# Unhandled Asynchronous Error in Node.js

This repository demonstrates a common error in Node.js applications: unhandled errors occurring within asynchronous callbacks. The `bug.js` file shows the problematic code, while `bugSolution.js` presents the corrected version using proper error handling.

The issue arises when an error is thrown inside a `setTimeout` callback within an Express.js route.  Without proper error handling, this error will not be caught, resulting in the server crashing.

**How to run:**

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `npm install` to install the dependencies.
4. Run `node bug.js` to see the unhandled exception.
5. Run `node bugSolution.js` to see the corrected version with proper error handling.
