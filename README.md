# Express.js Server Unresponsiveness with Long-Running Tasks

This repository demonstrates a common issue in Express.js applications where long-running tasks can block the event loop, leading to the server becoming unresponsive to new requests.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides a solution using asynchronous operations.