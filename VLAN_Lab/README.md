# VLAN & Trunking Lab

## Objective
Configure VLANs and trunking between switches and verify inter-VLAN communication.

## Topology
- 3 Switches
- 1 Router
- 
## Configuration Summary
- VLAN 10: IT
- VLAN 20: Sales
- VLAN 30: Admin
- VLAN 40: Marketing
- Trunk configured on switch ports
- Subinterfaces configured on router

## Verification
- Successful ping between VLANs
- `show vlan brief`
- `show interfaces trunk`
