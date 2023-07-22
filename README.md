# Terraform-vpc
By using this code we can create a vpc with three public subnets, three private subnets and three db subntes.
Once created the subntes it will create Internet gateway and attach to the created vpc.
After the IGW, it will create the elastic ip to allocate it for NAT Gateway.
Once created the EIP, Nat Gateway it will create in any one public subnet.
It will create the Route tables for public, private and db subntes.
For public route it will attach all the three public subntes and routes with IGW.
For private route it will attache all the three private subnets and route with NGW.
For db route it will attache all the three db subntes and route with NGW.
