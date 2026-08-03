# Project 03 - VLAN Configuration

## Objective

To configure VLANs on a Cisco 2960 Switch and logically separate departments using Virtual LANs.

---

## Devices Used

- 1 Cisco 2960 Switch
- 4 PCs

---

## VLAN Configuration

| VLAN ID | Department |
|---------|------------|
| 10 | HR |
| 20 | Finance |

---

## IP Addressing

| Device | IP Address | VLAN |
|---------|------------|------|
| PC0 | 192.168.10.10 | VLAN 10 |
| PC1 | 192.168.10.11 | VLAN 10 |
| PC2 | 192.168.20.10 | VLAN 20 |
| PC3 | 192.168.20.11 | VLAN 20 |

---

## Configuration Summary

- Created VLAN 10 (HR)
- Created VLAN 20 (Finance)
- Assigned Fa0/1–Fa0/2 to VLAN 10
- Assigned Fa0/3–Fa0/4 to VLAN 20
- Verified configuration using `show vlan brief`

---

## Verification

- PC0 → PC1 ✅ Successful
- PC2 → PC3 ✅ Successful
- PC0 → PC2 ❌ Failed (Different VLANs)

---

## Skills Learned

- VLAN Creation
- VLAN Naming
- Access Port Configuration
- Interface Range Configuration
- VLAN Verification
- Basic Layer 2 Network Segmentation

---

## Status

✅ Completed
