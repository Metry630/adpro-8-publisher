a. How many data your publlsher program will send to the message broker in one run?

The publisher will send 5 data to the message broker in one run.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

The publisher and the subscriber are using the same message broker to communicate.


![rabbit.png](img%2Frabbit.png)
![Screen Shot 2024-04-23 at 11.44.38.png](img%2FScreen%20Shot%202024-04-23%20at%2011.44.38.png)
![Screen Shot 2024-04-23 at 11.44.55.png](img%2FScreen%20Shot%202024-04-23%20at%2011.44.55.png)
The publisher has successfully sent 5 data to the message broker.
![Screen Shot 2024-04-23 at 12.10.07.png](img%2FScreen%20Shot%202024-04-23%20at%2012.10.07.png)
cThe spikes indicate the message rates of how many messages are sent within a time interval.
Because the publisher sends messages to the message broker the spikes appear.

![Screen Shot 2024-04-23 at 12.01.49.png](img%2FScreen%20Shot%202024-04-23%20at%2012.01.49.png)
