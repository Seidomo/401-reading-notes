### CLASS 19


# AWS: Events






## REVIEW, RESEARCH AND DISCUSS


- [**HOME**](https://seidomo.github.io/reading_notes/home)



### What’s the difference between a FIFO and a standard queue?

- FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.



### How can the server be assured a message was properly received?

- The reciepnt must emit a recieved event so then the server can remove the message from the queue.



### What classic design pattern is best represented by event driven programming?

- The Obserevr pattern.


### How do you test an event driven system?

- Using jest as a node library and writing tests that check for out puts.


## TERMS:


``` Serverless Api ```

- Serverless Api is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. A serverless application runs in stateless compute containers that are event-triggered



``` Triggers ```

- A trigger is a special type of stored procedure that automatically runs when an event occurs. 

```  Dynamo vs Mongo  ```

- DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas. ... DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents. DynamoDB supports limited data types and smaller item sizes.


- ``` Dynamoose vs Mongoose ```

- Dynamoose is a modeling tool for Amazon's DynamoDB while mongoose is a modeling tool for MongoDB.



- [attribiution](https://www.xplenty.com/blog/dynamodb-vs-mongodb-differences/#:~:text=DynamoDB%20is%20a%20fully%20managed,fully%20managed%20with%20MongoDB%20Atlas.&text=DynamoDB%20uses%20tables%2C%20items%20and,and%20has%20fewer%20size%20restrictions.)



- [**HOME**](https://seidomo.github.io/reading_notes/home)