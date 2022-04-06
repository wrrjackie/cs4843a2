# CS 4843-001
## Assignment 2: Developing infrastructure as code for a webapp

### In this assignment I took a big look at the policies and network securities needed to develop an Instagram-like app from the ground up. There are many rules when approaching to set boundaries and access points for different structures of a webapp's network links and server protections. 

#### The following files were created to set 
network.yml:
This template deploys a VPC, with a pair of public and private subnets spread across two Availabilty Zones. It deploys an Internet Gateway, with a default route on the public subnets. It deploys a pair of NAT Gateways (one in each AZ), and default routes for them in the private subnets.

servers.yml:


storage.yml:

