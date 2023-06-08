# AWS Global Infrastructure Overview
![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/f2bbf779-f970-40df-8648-8343b5291f9f)

The Global infrastructure provies High availability for application by creating a multi-AZ architecture balanced by a Distributed Elastic Load Balancer
![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/a2379806-30a5-4e65-8154-d560376b388b)
## Benefits of AWS Global Architecture
1. Performance ![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/354a6eff-029a-4647-94d0-97dff134e95a)

2. Security![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/eff46eb5-e647-40d4-882b-868219f3845f)

3. Scalability![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/1507eada-3c9e-4619-86af-2dbf9ac4c84d)

4. Low Cost ![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/ba5f6a3d-b57d-481d-9ac9-0266cd95635a)

## Amazon EC2 Instances
**Amazon EC2 Basics**
+ EC2 Storage![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/5f409777-f568-4ca1-9a70-dbaf4225804b)
+ EC2 Networking ![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/5b81d938-db9e-48eb-a914-7cdae6ff9e99)
+ Launch EC2 Instances - Summary Step by step cheat sheet on what is required to run an EC2 instance ![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/dfb0778c-705f-4a6e-8b60-4cbcb8f34fb8)
## Amazon Elastic Block Service
EBS - serves one instance at a time but one instances can be attached to multiple EBS volumes
![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/c6b7bfd3-32db-4de4-a360-e46126fea12a)

Provides persistent storage for EC2 instances
![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/f7e254a2-3fbb-41a7-9a73-f9e0fe05da87)
### Understanding the Difference Between IOPS vs ThroughPut
Consider the following [Article](https://www.buffalotech.com/blog/iops-vs-throughput-what-is-the-difference-and-how-do-they-affect-storage-performance#:~:text=IOPS%20measures%20the%20number%20of%20cars%20(i.e.%2C%20read%20and%20write,the%20highway%20in%20one%20second.) </br>
IOPS ensures Fast Response times from client request hence ensuring that there is no indiviidual delay while ThroughPut  ensures that A lot of Data can pass hrough the instance in such a shor period without fail.Throughput intensive is often when transferring large data workloads from one sysems to the other.
+ SSD -IOPS![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/00a93be6-e7c1-4eeb-b33f-db7b890fe224)
+ HDD- Throghput-intensive![image](https://github.com/lkiunga/AWS-Cloud-Engineer-Skills-Lab/assets/45036280/386cf9c5-473a-4f2e-a031-b2e8ea77cbca)



