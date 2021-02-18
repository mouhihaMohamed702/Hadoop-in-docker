# Hadoop Docker project(FPSB) 


## Created by: 

### Mouhiha Mohamed 

##  :pencil2:  Introduction 

--- 

## What is Docker?

The Apache™ Hadoop® project develops open-source software for reliable, scalable, distributed computing.

The Apache Hadoop software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures.
## What is a Docker Image?

Docker images are the basis of containers. Images are read-only, while containers are writeable. Only the containers can be executed by the operating system.

https://docs.docker.com/terms/image/
##  Objective :  

*  The purpose of docker-hadoop is to provide a full, standard, hadoop cluster that can be used for development or testing purposes.

Currently, it provides support for the following Hadoop distributions:

Apache Hadoop:
versions 3.*

  

### Installation 🔌of  the following tools in docker: 
---
*  Hadoop 

*  Kafka 

*  Spark 

* Hue 

* Hbase 

* Zookepeeper 

* zepplin 

* Hive 

* StreamSet 

  

  

  ##  :pencil2:  Som of interfaces graphics Screenshots 

 

--- 

#### Run this cmd `Sudo docker images `




![cd99eb56-408c-4a33-8fe8-90b8156801a7](https://user-images.githubusercontent.com/59533527/108103081-b423af00-7089-11eb-9d14-08c1c77239f2.jpg) 

 

  

  

  

#### Run this cmd `sudo docker-compose up  `

![compose-up](https://user-images.githubusercontent.com/59533527/108103291-05cc3980-708a-11eb-9f52-3e6a23445fd5.jpg)  

  

#### Go to http://localhost:50070 to view the current status of the system from the namenode: 

![namenode](https://user-images.githubusercontent.com/59533527/108104021-0c0ee580-708b-11eb-8e2e-e6b3665f5721.jpg) 

  

#### Go to http://localhost:8080 to view the current status of the system from the Spark Master: 

![sparkmaster](https://user-images.githubusercontent.com/59533527/108104660-e0402f80-708b-11eb-9db4-1d6dc38639c4.jpg) 

 

#### Go to http://localhost:8081 to view the current status of the system from the Spark Worker: 

![spark worker](https://user-images.githubusercontent.com/59533527/108104742-f77f1d00-708b-11eb-89c2-7cbb38f24d34.jpg) 

 

#### Go to http://localhost:18630 to view the current status of the system from the StreamSet: 

![streamSET](https://user-images.githubusercontent.com/59533527/108104811-0c5bb080-708c-11eb-8ac4-4406e300c27a.jpg) 

 

 

 

#### Go to http://localhost:16010 to view the current status of the system from the Hbase: 

![HBASE](https://user-images.githubusercontent.com/59533527/108104858-1da4bd00-708c-11eb-8263-b297e9cf4604.jpg) 

 ### Contributing 💡
 ---
If you want to contribute to this project and make it better with new ideas, your pull request is very welcomed.
If you find any issue just put it in the repository issue section, thank you.
## Thank You !

Please ⭐️ this repo and share it with others

  

##### tags:  `Hadoop` `Docker` `Kafka` `Spark ` `Hue ` `Hbase` `Zookepeeper` `zepplin` `Hive` `StreamSet`  
