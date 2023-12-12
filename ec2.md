## Task 1: Launching your EC2 instance

In this task, you launch an EC2 instance with termination protection. Termination protection prevents you from accidentally terminating an EC2 instance. You also deploy your instance with a user data script to deploy a simple web server.

In the AWS Management Console on the Services menu, enter EC2. From the search results, choose EC2.

In the left navigation pane, choose EC2 Dashboard to ensure that you are on the dashboard page.

In the Launch instance section, choose the Launch instance button.

- STEP 1: NAME YOUR EC2 INSTANCE

Using tags, you can categorize your AWS resources in different ways (for example, by purpose, owner, or environment). This categorization is useful when you have many resources of the same type. You can quickly identify a specific resource based on the tags that you have assigned to it. Each tag consists of a key and a value, both of which you define.

When you name your instance, AWS creates a key-value pair. The key for this pair is Name, and the value is the name that you enter for your EC2 instance.

In the Name and tags pane, in the Name text box, enter 
```
my-ec2-web-server
```
Choose the Add additional tags link.
From the Resource types dropdown list, 
```
select Instances and Volumes.
```
![images](./images/my-ec2-web-server.png)
___

- STEP 2: CHOOSE AN AMI

An Amazon Machine Image (AMI) provides the information required to launch an instance, which is a virtual server in the cloud. An AMI includes the following:

A template for the root volume for the instance (for example, an operating system or an application server with applications)
Launch permissions that control which AWS accounts can use the AMI to launch instances
A block device mapping that specifies the volumes to attach to the instance when it is launched
The Quick Start list contains the most commonly used AMIs. You can also create your own AMI or select an AMI from the AWS Marketplace, an online store where you can sell or buy software that runs on AWS.

Locate the Application and OS Images (Amazon Machine Image) section. It is just below the Name and tags section.
In the search box, enter 
```
Windows Server 2019 Base
```
 and press Enter.

Next to Microsoft Windows Server 2019 Base, choose Select.
Choose Confirm Changes.

![image](./images/my-ec2-web-server.png)
___
- STEP 3: CHOOSE AN INSTANCE TYPE

Amazon EC2 provides a wide selection of instance types that are optimized to fit different use cases. Instance types comprise varying combinations of CPU, memory, storage, and networking capacity and give you the flexibility to choose the appropriate mix of resources for your applications. Each instance type includes one or more instance sizes so that you can scale your resources to the requirements of your target workload.

In this step, you choose a 
```
t2.micro 
```
instance. This instance 
type has 1 virtual CPU and 1 GiB of memory.

In the Instance type section, keep the default instance type, t2.micro.

![screenshot](./images/instancetype.png)
___