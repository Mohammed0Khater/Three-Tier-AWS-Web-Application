# Three-Tier-web-application-on-AWS-
Three Tier web application on AWS 

This project was done as a graduation project from the AWS Re/Start program, governed by the Intensive Training Program offered by the Information Technology Institute (ITI) branch in Mansoura.

The project is a simple architecture of services combined together to create a working application that returns a string of text if all the layers are connected properly. The concepts of the Well-Architected Framework were preserved throughout the project, to the best of our ability, despite its simplicity:

* Availability was maintained through the usage of multiple AZs and instances along with a load balancer. 
* Operational Excellence was offered through automation of the deployment process through CloudFormation. 
* Reliability was ensured through failover routing and cross region replicas using Route53, as well as the usage of multiple AZs and instances along with a load balancer. 
* Security was maintained through the usage of proper IAM roles and permissions as well as the isolation of the data and application layers in private subnets as well as the utilization of security groups and NACL     to limit inbound network traffic at the instance and subnet levels respectively. 
* Cost Optimization was done through careful research of instance types and pre-allocating  costs using pricing calculator, as well as using cost explorer and tagging instances properly for aws organisations to enable consolidated billing. 
* Performance Efficiency was suggested through possible implementation of Auto Scaling Groups which allows us to set up a system of self-governing rules that can grow or diminish a system's capabilities after          reaching certain metrics on CloudWatch, also known as horizontal scaling.
* Sustainability suggestions were also given to make sure the instance types waste as little time idling as possible and save as much energy as possible to reduce harm to the environment. 

The project focuses on clean architecture execution using the Well-Architected Framework.



