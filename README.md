# terraform
terraform scripts
The ec2.tf script do following jobs
- creating a vpc
- creating two subnet one is private and one is public
- creating routing table and associating with the subnet
- creating NAT gateway for private subnet
- deploying  ec2 instance in public and private subnet

# workflow

<img src="./graph.svg">
