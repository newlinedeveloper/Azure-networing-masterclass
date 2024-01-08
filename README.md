## Azure Networking Masterclass

- Introduction
- Azure VNET Peering & Gateway
- Azure Hybrid Networking
- Azure ExpressRoute
- Azure Load balancing
- Azure Traffic Manager
- Azure Application Gateway
- Azure Front Door
- Azure DDoS Protection
- Azure Firewall
- Azure Virtual Network Service Endpoints
- Monitor Azure Networking

### Azure VNET Peering & Gateway

#### Introduction to Azure virtual networks
- Create virtual networks and subnets
  1. Create 3 Vnets -  CoreServicesVnet, ManufacturingVnet, ResearchVnet
  2. create subnets for each Vnets
- Configure DNS settings in Azure
  1. Create a private DNS Zone
  2. Link subnet for auto registration
  3. Create virtual machines to test the configuration
  4. Verify records are present in the DNS zone
- Connect two Networks using Global VNet Peering
  1. create a virtual machine to test the configuration
  2. connect to the Test VMs using RDP
  3. Test the connection between the VMs
  4. create VNets peerings between CoreServicesVnet and ManufacturingVnet
  5. Test the connection between the VMs
 

### Azure Hybrid Networking

- Create and configure a virtual network gateway
  1. Create CoreServicesVnet and ManufacturingVnet
  2. Create CoreServicesVM
  3. Create ManufacturingVM
  4. Connect to the Test VMs using RDP
  5. Test the connection between the VMs
  6. Create CoreServicesVnet Gateway
  7. Create ManufacturingVnet Gateway
  8. CoreServicesVnet to ManufacturingVnet
  9. Connect ManufacturingVnet to CoreServicesVnet
  10. Verify that the connections connect
  11. Test the connection between the VMs
- Create a virtual WAN by using Azure Portal
  1. Create a virtual WAN
  2. Create a hub by using Azure portal
  3. Connect a VNet to the Virtual Hub
  4. Clean up resources

### Design and Implement Azure ExpressRoute
- create VNet and subnets
- Create Vnet Gateway with ExpressRoute option
- Create Express Router 

### Azure Load balancing
- Create the Virtual network
- Create backend servers
- create the load balancer
- Create the load balancer resources
- Test the load balancer
