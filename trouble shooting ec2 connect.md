## EC2 refusing to connect to intance?

if the error message suggests that it cannot connect to SSH, double check
VPC, allowing all DNS Settings
subnet connections are public
internet gateways are linked
route tables are linked
security groups are linked and have the proper boundaries set
