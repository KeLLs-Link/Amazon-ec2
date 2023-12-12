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

STEP 2: CHOOSE AN AMI