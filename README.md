Business Problem:
Due to the trending features of cloud resources are being deployed to cloud on demand. This may lead to running of compute without any CPU utilization and thus generating cost for not using those resources also.  To overcome this we can auto stop the instance based on predefined metric like CPU utilization for compute instance, memory utilization for volume.

Solution for this kind of scenarios is to use serverless capabilities in cloud to automatically maintain resources effectively that are being deployed.

Steps involved are :

1.Create cloud watch  alaram that can track the usage of EC2 cpu.
2.Create a lambda function that gets triggred to stop the EC2 instance with low CPU utilization.



