# Day 1

## Daily Journal
Read Asynchronous Code > Callback Hell and answer the following questions
1. What are some of the signs and causes of Callback Hell?
A sign of callback hell are when callback functions have multiple nested functions with multiple }) closing brackets, and when the functions read top to bottom rather than having a separate module with the functions used for the callback.
2. What does the asynchronous mean and how are callbacks involved?
Asynchronous or Async means its code you want to execute later in time, usually when some other action occurs. Callbacks aren't actually part of the javascript language, its just a way to execute a function using the concept of async.
3. Summarize the 3 ways to avoid / fix Callback Hell
A way to fix callback hell is to use multiple modules to export the functions used in the callback, that way the callback function itself is only few lines and is much easier to read and is more clear what the code is doing.