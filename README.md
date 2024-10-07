# Kafka-Projects

Sample Project for Kafka Listener.

Steps:

1) Goto https://kafka.apache.org/quickstart -> Install Kafka if not yet installed

2) Look for Kafka with Zookeeper and run the two commands in seperate terminal sessions.

3) Clone the project and run the maven build.

4) To read the messages, Open another terminal session and use the command $ bin/kafka-console-consumer.sh --topic quickstart-events --from-beginning --bootstrap-server localhost:9092

5) Use Postman API with POST Request with URL: http://localhost:8080/api/v1/messages and body

{
    "message": "(Type Message Here)"
}
