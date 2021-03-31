# Day 3 

## Daily Journal
Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions
1. What are the two common operations that we will set in the handler?
Most of the time, the main function of the handler object will be the get and set methods.
2. What do you have to make sure you are doing with every Get to insure the value does not become undefined?
You must return a value in a get method, if you simply use a console log it will log undefined because a value was never returned.
3. What are some of the benefits of the proxy object that we are using in our structure for applications?
Often times, creating proxy objects allows you to modify or remove the default functionality of an object, so data can be stored as private or so specific methods aren't able to be invoked.