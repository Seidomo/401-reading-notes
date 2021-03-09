### CLASS 16


# AWS S3 And Lambada






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


``` server instances ```



``` containers  ```


``` cloud services ```


``` cloud architecture ```


``` AWS ```

``` EC2/Beanstalk vs Heroku ```
