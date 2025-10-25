# Lab08 — OSPFv2 Multi-Area

**Goal:**  
Implement and verify Multi-Area OSPFv2 topology with backbone (Area 0) and non-backbone areas.

**Devices:**  
- R1, R2, R3 — Routers  
- D1, D2 — L3 Switches  

**Topology:**  
![Topology](1.png)

**Files:**  
- `OSPFv2_MultiArea.yaml` — CML topology  
- `R1_config.txt`  
- `R2_config.txt`  
- `R3_config.txt`  
- `D1_config.txt`  
- `D2_config.txt`

**Verification:**  
- OSPF neighbor relationships across multiple areas  
- ABR operation and inter-area routing  
- LSDB synchronization  
- Reachability between networks in different areas
