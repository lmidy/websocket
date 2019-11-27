# websocket

![Simplemessage Broker Diagram](https://github.com/lmidy/websocket/blob/master/message-flow-simple-broker.png)

Source: (https://docs.spring.io/spring-framework/docs/5.0.0.BUILD-SNAPSHOT/spring-framework-reference/html/websocket.html)


Notes: this is running on localhost:8081, if you want it to run in port 8080 just delete the values in the application.properties
I was running two different versions to compare differences, I figured out it was the spring version in my pom.xml file is what was causing the scheduler to not publish data to topic
