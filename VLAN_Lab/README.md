# VLAN & Trunking Lab

## Objective
Configure VLANs and trunking between switches and verify inter-VLAN communication.

## Topology
- 2 Switches
- 1 Router (Router-on-a-stick)

## Configuration Summary
- VLAN 10: Sales
- VLAN 20: HR
- Trunk configured on switch ports
- Subinterfaces configured on router

## Verification
- Successful ping between VLANs
- `show vlan brief`
- `show interfaces trunk`
