# CodeAlpha_NetworkIDS_Snort

## Objective
To implement a Network Intrusion Detection System (IDS) using Snort and detect ICMP traffic using custom rules.

## Tools Used
- Kali Linux
- Snort 3.12.2.0
- Nano Editor
- Ping Utility

## Implementation Steps
1. Install Snort
2. Verify Installation
3. Identify Network Interface
4. Create Custom Rule
5. Run Snort IDS
6. Generate ICMP Traffic
7. Detect Alerts

## Custom Rule

```snort
alert icmp any any -> any any (msg:"ICMP Ping Detected"; sid:1000001; rev:1;)
