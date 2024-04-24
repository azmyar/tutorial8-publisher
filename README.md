## Reflection

**a. How many data your publlsher program will send to the message broker in one run?**

The amount of data that the publisher program sends to the message broker during one operation depends on the application's unique configuration and requirements. This could transmitting a single message, multiple messages, or a continual flow of data.

**b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?**

Using the URL "amqp://guest:guest@localhost:5672" in both the publisher and subscriber programs indicates they are linked to the same AMQP message broker.

### RabbitMQ as Message Broker
   ![image](./img/15672(0_Connection).png)
### Sending and Receiving Message
##### Publisher Terminal
   ![image](./img/Publisher_Terminal.png)
##### Subscriber Terminal
   ![image](./img/Subscriber_Terminal.png)

### RabbitMQ Dashboard (1 Connection)
   ![image](./img/15672(1_Connection).png)