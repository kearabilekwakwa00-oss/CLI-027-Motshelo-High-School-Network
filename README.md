# CLI-027-Motshelo-High-School-Network
Network design and implementation project for CLI-027 — Motshelo High School (Taung), covering VLAN segmentation, OSPF Area 0, IP addressing, WAN redundancy, and secure Reception kiosk access.
he project designs and simulates a secure, segmented and resilient school network in Cisco Packet Tracer using the assigned address block **172.30.8.0/23**.

## Client Information
- **Client ID:** CLI-027
- **Organisation:** Motshelo High School (Taung)
- **Industry:** Education
- **Assigned network:** 172.30.8.0/23
- **Simulation:** Cisco Packet Tracer

## Assigned Networking Challenge
**Basic OSPF using a single Area 0.** Internal school networks are advertised through OSPF and verified using neighbour, routing-table and connectivity tests.

## Main Requirements
- VLAN segmentation for Administration, Teachers, Students, Finance, Servers, Management and the Reception Kiosk.
- Primary Internet/WAN path through R1/ISP1.
- Separate backup Internet/WAN path through R2/ISP2 for Finance.
- Reception kiosk in VLAN 70 with Internet-only access.
- ACL/firewall-style restriction preventing the kiosk from reaching internal school VLANs.
- End-to-end connectivity, OSPF and Finance failover testing.
