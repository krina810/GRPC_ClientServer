

To run Server or Client in JAVA: Go to grpcDemo/grpc-java

$ cd GRPC_ClientServer/grpc-java $ mvn install

Run GRPC JAVA Server:

$ cd GRPC_ClientServer/grpc-java/simple-grpc-server $ mvn install exec:java -Dexec.mainClass=demo.helloworld.grpc.server.MyGrpcServer

Run GRPC JAVA Client:

$ cd GRPC_ClientServer/grpc-java/simple-grpc-client $ mvn install exec:java -Dexec.mainClass=demo.helloworld.grpc.client.MyGrpcClient


Run with docker-compose:

$ sudo docker-compose build
$ sudo docker-compose up
