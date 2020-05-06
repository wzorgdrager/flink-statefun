# How to run
Build the Flink Statefun image:  
```bash
cd statefun-image && docker build . -t flink-statefun
```  
Start the Flink cluster, Kafka broker, ZK instance and deploy the stateful functions using:  
```bash
docker-compose up -d
```  
To see the the logs:  
```
docker-compose logs -f event-generator 
```
