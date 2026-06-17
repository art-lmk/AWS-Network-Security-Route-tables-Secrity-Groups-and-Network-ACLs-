<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# VPC Traffic Flow and Security

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-networks-security)

**Author:** Lenah Mbatha  
**Email:** lenahmbatha5@gmail.com

---

## VPC Traffic Flow and Security

![Image](http://learn.nextwork.org/lively_rose_silly_raspberry/uploads/aws-networks-security_92b0b0b4)

---

## Introducing Today's Project!

### What is Amazon VPC?

### How I used Amazon VPC in this project

### One thing I didn't expect in this project was...

### This project took me...

---

## Route tables

Route tables are tables containing rule or instructions that decide where the data in your network should go to

Routes tables are needed to make a subnet public because they control traffic where it is allowed to go

![Image](http://learn.nextwork.org/lively_rose_silly_raspberry/uploads/aws-networks-security_0a07b191)

---

## Route destination and target

Routes are defined by their destination and target, which mean ;
1. destination - the ip address range that the traffic wants to reach
target- the road or the path that the traffic willhave to take to rach its destination

The route in my route table that directed internet-bound traffic to my internet gateway had a destination of 0.0.0.0/0 and a target of igw-052a8b6c90792675f

![Image](http://learn.nextwork.org/lively_rose_silly_raspberry/uploads/aws-networks-security_0a07b191)

---

## Security groups

Security groups are security checkpoint embedded in each resource in a vpc

### Inbound vs Outbound rules

Inbound rules are rules that govern that data that enters your resources in your security group. I  configured an inbound rule that allows users to access my webiste

Outbound rules are the rules that govern the data that your resourcescan send out. By default, my security group's outbound rule are allowed in my AWS account

![Image](http://learn.nextwork.org/lively_rose_silly_raspberry/uploads/aws-networks-security_92b0b0b4)

---

## Network ACLs

Network ACLs are security checkpoints that makes sure only authorized data comes in and out of a subnet

### Security groups vs. network ACLs

The difference between a security group and a network ACL is that in a security group, traffic rules apply at a resource level while in a network access controllist, traffic rules apply at a subnet level

---

## Default vs Custom Network ACLs

### Similar to security groups, network ACLs use inbound and outbound rules

By default, a network ACL's inbound and outbound rules will allow data to come in and out of a subnet, not unless configured otherwise

In contrast, a custom ACL’s inbound and outbound rules are automatically set to deny untill you set the rules to show which data packet traffic is allowed

![Image](http://learn.nextwork.org/lively_rose_silly_raspberry/uploads/aws-networks-security_4faeb056)

---

## Tracking VPC Resources

---

---
