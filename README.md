# Volume-Weighted-Average-Price
  This project consists 4 applications that I develop and some technologies. This technologies are Docker, Apache Kafka, Apache Zookeeper, Apache Spark.

  The main purpose of this project is an scalable data processing. Through Apache Kafka, it buffers data and pushs to consumers. Through Apache Spark, it processes fast data.
  
  Each application is in a Docker container. Through Docker-compose, launch full stack with oneliner: `docker-compose up`.       This is [docker-compose.yml](docker-compose.yml) file.
  
  Project architecture is as shown below:
  ![alt tag](vwap.png)
  
  You can access [slide](http://www.slideshare.net/BarCirit/volume-rated-average-price) of this project.
  
  To look details of producer and consumer applications, here are links: [producer](https://github.com/brscrt/kafkaProducer), [kafka consumer](https://github.com/brscrt/kafkaConsumer), [spark consumer](https://github.com/brscrt/SparkKafkaConsumer), [vert.x consumer](https://github.com/brscrt/Vert.xKafkaConsumer)
