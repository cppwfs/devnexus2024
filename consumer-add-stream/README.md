
Set the following properties in your application.properties file
spring.application.name=consumer
spring.cloud.function.definition=logIt
spring.cloud.stream.function.bindings.logIt-in-0=input
spring.cloud.stream.bindings.input.destination=pTest