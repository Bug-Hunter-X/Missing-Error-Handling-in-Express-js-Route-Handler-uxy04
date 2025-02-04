# Missing Error Handling in Express.js Route Handler

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling.  The `bug.js` file contains code that attempts to access a user by ID without checking for the existence of the user. This can result in unexpected behavior or even crashes if the user ID is invalid.

The `bugSolution.js` file provides a corrected version of the code that includes robust error handling.