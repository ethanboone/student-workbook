# Day 2

## Daily Journal
Read Asynchronous Code > JavaScript Promises and answer the following questions
1. What are the three states of a Promise?
Pending, resolved, rejected.
2. How do promises seek to resolve the issues of "callback hell"?
When using callbacks with promises, attaching callbacks to the promises rather than passing the callbacks makes the code much more digestable and easy to read.
3. What is the difference between .then() and .catch()?
The then method is what will happen once a promise is resolved, and the catch method can be used after the then method in the case the promise is rejected and doesn't complete it's specified functionality.