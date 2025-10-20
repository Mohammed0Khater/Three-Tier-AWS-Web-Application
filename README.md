# Three-Tier-web-application-on-AWS-
Three Tier web application on AWS 

This project was done as a graduation project from the AWS Re/Start program, governed by the Intensive Training Program offered by the Information Technology Institute (ITI) branch in Mansoura.

The project is a simple architecture of services combined together to create a working application that returns a string of text if all the layers are connected properly.
It also offers redundancy and availability due to the multiple EC2 (self-managed servers service) and RDS (AWS-managed relational database service) instances that offer an alternative in case one of the two goes down.

Isolation is also offered, by only keeping the Classic Load  to stay in the public subnet, and keeping all EC2 and RDS instances in a provate subnet to limit inbound traffic to them. This is important as it increases the security of the architecture.
