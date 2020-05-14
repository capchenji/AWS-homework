# AWS-homework
This is AWS homework for CLPSEC team training

`VPC`

In this task, you are asked to create a VPC, subnets inside VPC and a lambda function.

`VPC requirements`:
CIDR: 10.12.0.0/16

`Subnet:`
2 public Subnet, 2 private subnet

`Lambda:`
Lambda will return a hello world.
A lambda function which sits on one of private subnets

`Bonus:`
Create a smallest RDS, it sits inside one of private subnets.
Lambda can connect to this RDS.

Please do it manually first, then implemented with Terraform.