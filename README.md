# Kafka Producer using Spring Boot
> ![image](https://github.com/user-attachments/assets/807640c2-2139-4a89-949b-14d462c40c60)
_____________________________________________________________________________________________________
## Required Dependency 
> Spring Web
> Spring for Apache Kafka
> ![image](https://github.com/user-attachments/assets/6129c4c5-f906-4b02-bb7f-42629f5afdd7)
_____________________________________________________________________________________________________
##  To produce messages from Kafka topics with Spring Boot

> ### 1. Run the Apache Zookeeper server
> #### C:\kafka>.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
> ![image](https://github.com/user-attachments/assets/f8161510-d738-4adf-a05a-ed61f3fe4e78)
> ### 2. Run the Apache Kafka  server
> #### C:\kafka>.\bin\windows\kafka-server-start.bat .\config\server.properties
> ![image](https://github.com/user-attachments/assets/be02536b-1c7c-4585-b562-d9521f18b670)
> ### 3. Send the messages from Kafka Topics
> #### C:\kafka>.\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic NewTopic
> ![image](https://github.com/user-attachments/assets/62363342-5cb7-41df-a9d2-8235b29f4a26)
_____________________________________________________________________________________________________
## Postman CURL
> curl --location --request GET 'http://localhost:8081/publish/Kafka_Producer_Consumer_Test'
_____________________________________________________________________________________________________
## Final Output
> ![image](https://github.com/user-attachments/assets/a9e573db-e780-4bc7-a16e-0f793e32fc8d)

_____________________________________________________________________________________________________
# !! Thank You !!
