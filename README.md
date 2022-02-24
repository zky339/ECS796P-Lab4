# ECS796P-Lab4
Based upon https://github.com/sajeerzeji/SpringBoot-GRPC
Commands for preparing the enviornment (Assuming you are in the main folder e.g. the one with the pom.xml file in it)
1. sudo apt update
2. sudp apt install default-jdk maven git
3. git clone https://github.com/zky339/ECS796P-Lab4.git
4. cd ECS796P-Lab4
5. cd grpc-server
6. (From grpc-server folder) mvn package -Dmaven.test.skip=true
7. (From grpc-server folder) chmod 777 mvnw
8. (From grpc-server folder) ./mvnw spring-boot:run -Dmaven.test.skip=true
9. cd ECS796P-Lab4/grpc-client
10. (From grpc-client folder e.g. seperate ssh connection) mvn package -Dmaven.test.skip=true
11. (From grpc-client folder e.g. seperate ssh connection) chmod 777 mvnw
12. (From grpc-client folder e.g. seperate ssh connection) ./mvnw spring-boot:run -Dmaven.test.skip=true

