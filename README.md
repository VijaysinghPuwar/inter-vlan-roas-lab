# Inter‑VLAN Routing via Router‑on‑a‑Stick (Mini Lab)

Hands‑on Packet Tracer exercise that solidifies VLAN fundamentals ahead of my upcoming *OfficeNet 3‑Way Subnet* project.

## Topology
- **Router**: ISR 4331 (Gi0/0/0 trunk ➜ VLAN 10 & 20 sub‑interfaces)
- **Switch**: Catalyst 2960‑24TT (Gi0/1 trunk, Fa0/1 VLAN 10, Fa0/2 VLAN 20)
- **Hosts**: PC0 (192.168.10.10/24), PC1 (192.168.20.20/24)

## Key Skills Practiced
- VLAN creation & access‑port mapping  
- 802.1Q trunk configuration  
- Router‑on‑a‑stick inter‑VLAN routing  
- IOS verification (`show vlan`, `show interfaces trunk`, `show ip route`)  
- Basic troubleshooting methodology

## Files
- `configs/` – running‑configs for router & switch  
- `report/`  – PDF lab report + thumbnail  
- `packet‑tracer/` – .pkt topology file  

Feel free to fork, clone, and adapt for your own CCNA study sessions!
