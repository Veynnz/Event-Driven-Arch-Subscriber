# Module 9 Subscriber

1. What is AMQP?

AMQP is a standard set of rules that allows different computer programs to send and receive messages reliably. It ensures that messages can be passed between systems in a structured way.

------------------------------------

2. What does `guest:guest@localhost:5672` mean?

This string is a common URI or connection string used to specify how to connect to an AMQP broker.

- guest:guest: These are the username (first) and password (second) used to log in.
- localhost: This refers the host address of the AMQP broker. `localhost` meaning the broker runs on the same machine as the client app.s
- 5672: This is the specific port number the service uses for connections.
