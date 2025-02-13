# Node.js Server Hang Issue

This repository demonstrates a common issue in Node.js applications: the server hanging due to long-running operations that block the event loop.  The `server.js` file contains code that simulates a long-running operation, causing the server to become unresponsive.

The solution, in `serverSolution.js`, demonstrates how to avoid this issue using asynchronous operations and proper event loop management.