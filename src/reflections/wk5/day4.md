# Day 4
No journal, just hackathon
https://ethanboone.github.io/hackathon/
## Daily Journal
Read Servers with Node/Express > MongoDb Relationships and answer the following questions
1. What is a virtual property?
A virtual property is a property not saved to memory but can be assigned with data provided from the client side request.
2. When might you use a virtual property?
A time you would use a virtual property would be when assigning a user that created an element being displayed to the DOM, the data about the user would be sent in the request to the server and that virtual property will add the key/value to the response back to the client side but won't save that property into the database.
3. How do you search by a virtual properties value?
You can't access a virtual property with document queries or field selection, only standard properties can.