# VLAN Security Implementation
## Overview
Enterprise network segmentation project implementing secure VLANs using Cisco Packet Tracer for Development, HR, and Management departments.

### Project Highlights
- Secure VLAN implementation with inter-VLAN routing
- Access Control Lists (ACLs) for traffic control
- DHCP server configuration for automated IP assignment
- Port security and VLAN hopping prevention measures

## Network Architecture
### Network Topology
```
Core Switch (L3) 
├── VLAN 10 (Development) - 192.168.10.0/24
├── VLAN 20 (HR) - 192.168.20.0/24
└── VLAN 30 (Management) - 192.168.30.0/24
```

### VLAN Details
|
 VLAN ID 
|
Department  
|
 Subnet           
|
 Gateway        
|
 DHCP Range     
## Implementation Steps
1. Initial Setup
   - Device naming
   - Basic security configurations
   - Interface configurations

2. VLAN Configuration
   - VLAN creation
   - Port assignments
   - Trunk configuration

3. Security Measures
   - Port security
   - VLAN hopping g prevention
   - ACL implementation

## Configuration Examples
### Basic Switch Security
```cisco
enable secret class
line console 0
 password cisco
 login
line vty 0 4
 password cisco
 login
service password-encryption
```

### Testing Procedures
- [ ] Inter-VLAN connectivity verification
- [ ] ACL testing
- [ ] DHCP functionality
- [ ] Security measure validation

## Screenshots
[Place screenshots here showing:]
- Network topology
- VLAN configurations
- ACL settings
- Test results
