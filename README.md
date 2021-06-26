# AWS Transit Gatway Demo 

- Demo1: Multi VPC Interconnect
  - Create a stack using TGW-multi-vpc-interconnect.yaml
- Demo2: Shared VPC for Internet connection (Individual VPCs exclude shared VPC can't connect each other.)
  - Create a stack using TGW-shared-public-vpc.yaml
- Demo3: TGW Peering Inter region connection demo


# Demo1: Multi VPC Interconnect Architecture
Each Instance can be connected by using SSM Session Manager.

![tgw-Interconnect-vpcs](./images/tgw-Interconnect-vpcs.png)


# Demo2: Shared VPC for Internet connection Architecture
Each Instance can be connected by using SSM Session Manager.

![tgw-shared-public-vpc](./images/tgw-shared-public-vpc.png)
