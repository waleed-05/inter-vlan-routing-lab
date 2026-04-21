# inter-vlan-routing-lab

OBJECTIVE:
Enable communication between VLAN 100 (IT) and VLAN 200 (Sales).

 Network Overview:
 
4 switches (layer 2)
1 router (layer 3)
trunk links between switches
router-on-a-stick used

How it works (simple likhna):

switches VLAN create karte hain
trunks VLAN traffic carry karte hain
router subinterfaces routing karta hai

 Output:
 
Devices in VLAN 100 can communicate with VLAN 200 via router.
DHCP assigns IP automatically.

 Security relevance :
 
- VLANs isolate departments (IT vs Sales)
- Trunk links carry multiple VLANs securely
- Router enforces controlled inter-VLAN communication
- DHCP reduces manual configuration errors


Possible attack:
- VLAN hopping

Mitigation:
- Proper trunk configuration
- Restrict allowed VLANs
