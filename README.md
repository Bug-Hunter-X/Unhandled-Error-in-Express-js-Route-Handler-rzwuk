# Unhandled Error in Express.js Route Handler

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling when dealing with user input.

The `bug.js` file shows an example of a route handler that is vulnerable to errors if the `:id` parameter is not a valid number or if a user with that ID does not exist.

The `bugSolution.js` file provides a corrected version of the handler with improved error handling.  This includes explicitly checking for valid input and returning appropriate HTTP status codes for different error scenarios.