# Day 4

## Daily Journal
Read Advancing with JS > The Observer Pattern and answer the following questions
1. What problems does the Observer Pattern seek to solve?
The observer patter solves the common problem of one-to-many, one-way, and event drive data binding. This issue arises when numerous elements must be in sync with one another.
2. What are the three mechanisms of the observer pattern?
The observer pattern uses the subscribe method to add new events to the observer array, the unsubscribe method that removes events from the same array, as well as the broadcast method which calls all events in the observer array with an arrow function in a forEach loop, which allows the desired one-to-many relationship between the the events and the observer.
3. Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
