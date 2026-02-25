Initial SOC lab documentation 
# SOC Lab: Network Traffic Analysis

## Objective
To analyze ICMP and DNS traffic using Kali Linux and Wireshark.

## Tools Used
- Kali Linux
- Wireshark
- ping
- ip a

## Lab Steps

### 1. Checked Network Interface
Used:
ip a

### 2. Generated Traffic
ping google.com

### 3. Captured Traffic in Wireshark
Captured packets on eth0 interface.

### 4. Applied Filters
icmp
dns

## Security Relevance
Understanding ICMP and DNS traffic helps detect:
- Network reconnaissance
- DNS tunneling
- Ping sweeps
