[//]:![](images\image1a.png)

![](images\mq-title.png)

**What is a Proof of Technology?**

Proof of Technology sessions are complimentary classes to build
understanding of IBM technology and software with practical
presentations and hands-on lab exercises. 

**What is IBM MQ?**

You can use IBM MQ to enable applications to communicate at different times and in many diverse computing environments.

IBM MQ is messaging for applications. It sends messages across networks of diverse components. Your application connects to IBM MQ to send or receive a message. IBM MQ handles the different processors, operating systems, subsystems, and communication protocols it encounters in transferring the message. If a connection or a processor is temporarily unavailable, IBM MQ queues the message and forwards it when the connection is back online.
An application developer has a choice of programming interfaces, and programming languages to connect to IBM MQ.


## Lab section:
Before starting the labs you should review the lab environment and the use of the VDI desktop you will be using along with the OCP cluster to complete the labs.<br>
[*WorkShop 1:*](https://techzone.ibm.com/my/workshops/student/642ee57affb9a60017778383)

[*WorkShop 2:*](https://techzone.ibm.com/my/workshops/student/64359e5062cce60016d749ab)


|  Topic                                | Description                                                                
|---------------------------------------|-----------------------------------------------------------------------------|
| [Introducing MQ RDQM](HA-intro/index.md)          | This section will introduce you to IBM MQ Replicated Data Queue Manager.  
|---------------------------------------|-----------------------------------------------------------------------------|   
| [MQ Streaming queues](StreamQ/README.md)         | This section you will tap into the value of existing data flowing over MQ with zero impact to the existing applications or their messages, and without a need for re-architecture your message flows.
|---------------------------------------|-----------------------------------------------------------------------------|     
| **MQ Uniform Clusters**        | This section you will see how Uniform clusters enables applications to be workload balanced across loosely coupled queue managers  
|---------------------------------------|-----------------------------------------------------------------------------|     
| [MQ RDQM DR](DR/index.md)          | You can create a primary instance of a disaster recovery queue manager running on one server, and a secondary instance of the queue manager on another server that acts as the recovery node. Data is replicated between the queue manager instances.
|---------------------------------------|-----------------------------------------------------------------------------|
| [MQ RDQM DR/HA Group](DR_HA_group/index.md)          | You can configure a replicated data queue manager (RDQM) that runs on a high availability group on one site, but can fail over to another high availability group at another site if some disaster occurs that makes the first group unavailable. This is known as a DR/HA RDQM.



<!--- <[MQ Uniform Clusters](Uniform/README.md > --> 
<!--- <[ACE Toolkit Labs](ACE-toolkit-labs/index.md) > -->
<!--- <[Event Endpoint Labs](Event_EndPoint/index.md) > -->
<!--- <[Aspera Labs](Aspera/index.md) > -->
