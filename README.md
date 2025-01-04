# Express.js Route Handler Bug: Missing Error Handling

This repository demonstrates a common error in Express.js route handlers:  failure to handle invalid input gracefully. The code includes a route that fetches a user by ID.  However, it lacks proper error handling if the provided ID is not a valid number, potentially leading to crashes or unexpected behavior.

The `bug.js` file contains the erroneous code.  The `bugSolution.js` file provides a corrected version with robust error handling.