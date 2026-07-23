# azure-virtual-network-lab
AZ-104 hands-on lab covering Azure VNet, subnets, NSGs and connectivity.

# Azure Virtual Network Lab

## Objective

Deploy and configure an Azure virtual network with multiple subnets,
Network Security Groups and virtual machines.

## Resources Created

- Resource group
- Virtual network
- Frontend subnet
- Backend subnet
- Network Security Group
- Two Azure virtual machines
- Network interface cards

## Architecture

Internet
   |
Public IP
   |
Frontend VM
   |
Frontend Subnet
   |
Backend Subnet
   |
Backend VM

## Implementation Steps

1. Created an Azure resource group.
2. Created a virtual network.
3. Configured frontend and backend subnets.
4. Created Network Security Groups.
5. Applied security rules to the subnets.
6. Deployed two Azure virtual machines.
7. Tested communication between the virtual machines.

## Skills Demonstrated

- Azure networking
- IP address planning
- Subnet configuration
- NSG configuration
- Virtual machine deployment
- Connectivity troubleshooting

## Lessons Learned

This lab improved my understanding of subnet communication,
security rules and Azure network troubleshooting.
