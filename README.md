# kafka-clustering

This repository has all the information about kafka clustering.
Will create 3 kafka brokers

1. First we will create server-1.properties file.
2. Second we will create server-2.properties file.
3. Third we will create server-3.properties file.
4. No need to change in zookeeper.properties file.
5. Because we want only single zookeeper server for all brokers.
6. Will start zookeeper server then will start server-1, server-2 and server-3 etc.
7. Now we can start our applications if server-1 is down then application will coordinate to another brokers like server-2,
   if server-1, and server-2 are down then application will coordinate with server-3.
   
