# Day 2
https://ethanboone.github.io/day2afternoonchallenge/
## Daily Journal
Read Servers with Node/Express > MongoDb Relationships and answer the following questions
1. What are the three types of relationships?
One to one, one to many, and many to many.
2. What are the benefits of the traditional linking of relationships instead of Embedding
You don't have to worry about hitting maximum document size, sacrificing application performance, or returning specific data without iterating throughout the entire embedded array.
3. What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
In the case a data's category or relationship to other similar data is extensive to the point it will impede run time, you wouldn't want to utilize two way embedding, instead opting for one way embedding or if the data has multiple relationships between each other you would use third collection embedding to store the data in a separate collection.