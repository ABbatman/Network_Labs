# Lab09 — OSPFv2 Summarization and Filtering

**Goal:**  
Configure and verify route summarization and filtering in OSPFv2 across multiple routers.

**Devices:**  
- R1, R2, R3 — Routers  
- D1, D2 — L3 Switches  

**Topology:**  
![Topology](1.png)

**Files:**  
- `OSPFv2_Summarization_Filtering.yaml` — CML topology  
- `R1_config.txt`  
- `R2_config.txt`  
- `R3_config.txt`  
- `D1_config.txt`  
- `D2_config.txt`

**Verification:**  
- OSPF summarization between areas  
- Route filtering using prefix-lists and distribute-lists  
- Default route origination  
- Connectivity between summarized and filtered networks
