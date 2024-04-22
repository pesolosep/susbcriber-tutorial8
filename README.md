- Muhammad Faishal Adly Nelwan
- 2206030754/Advanced Programming C


# what is amqp?
*amqp* (Advanced Message Queuing Protocol) is a protocol used for passing messages between system applications. It ensures that data sent from one point reaches another through a middleware of message queues and rules for handling the messages, known as routing.

# what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for? 

1. First `guest`: This is the username for the AMQP server. In this case, 'guest' is a common default username used in many AMQP installations, particularly in RabbitMQ.
2. Second `guest`: This is the password associated with the username. Here again, `guest` is the default password often paired with the default `guest` username in default configurations.
3. `localhost`: This part of the string specifies the hostname or the IP address where the AMQP server is running. `localhost` specifically refers to the local machine, meaning the server is running on the same machine as the client trying to connect. This is typical for development or test environments.
4. 5672: This is the port number on which the AMQP server is listening. Port 5672 is the standard port for AMQP 0-9-1 without encryption (AMQP over TCP). If encryption were used (AMQP over TLS), the standard port would typically be 5671.

So, `guest:guest@localhost:5672` effectively tells the client software to log into the AMQP server running on the local machine using the default port 5672, with the username `guest` and the password `guest`. This connection string is used to establish a connection to the message broker for sending or receiving messages.