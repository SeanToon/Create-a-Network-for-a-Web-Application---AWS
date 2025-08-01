# Create-a-Network-for-a-Web-Application---AWS

In this project I will be setting up a secure network for a new web application. In the process I will gain knowledge about the basics of networking on AWS.
To set up the network I will:
  1. Create a VPC with four subnets
  2. Attach an internet gateway and route table
  3. Create a security group with the proper inbound rule
  4. Launch an EC2 instance and bootstrap the web application

Creating the VPC
Search for VPC, Select VPC and then click "Create VPC"


Enter resources 
Select "VPC only", enter a name tag, "IPv4 CIDR manual input", input CIDR block size, then scroll down to end of page and click "Create VPC"


After successful creation of VPC
Copy the VPC ID for later, click "Actions" dropdown, choose "Edit VPC settings"


Edit VPC settings
Enable DNS hostnames
