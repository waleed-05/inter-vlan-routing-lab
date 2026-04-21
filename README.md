# Inter-VLAN Routing Lab

## Objective
Enable communication between VLAN 100 (IT) and VLAN 200 (Sales)

## Topology
See topology.png

## Configuration
Configs are available in the /configs folder

## How it works
- Switches create VLANs
- Trunks carry VLAN traffic
- Router routes between VLANs

## Result
Devices from different VLANs can communicate

## Security Relevance
- VLANs isolate departments
- Router controls communication


Possible attack:
- VLAN hopping

Mitigation:
- Proper trunk configuration
- Restrict allowed VLANs
