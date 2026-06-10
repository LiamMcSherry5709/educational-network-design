# Testing 

The purpose of this test plan is to demonstrate that the basic connectivity within the network.  This prototype network is used to test various aspects of the proposed design.   
 
•	Test 1: Baseline Connectivity Test   
•	Verify physical and IP connectivity between devices on the prototype network. 
•	Collect operational baselines. 
•	Demonstrate IP connectivity between devices. 


## Equipment 

<img width="808" height="696" alt="Screenshot 2026-05-29 112848" src="https://github.com/user-attachments/assets/135c112f-d464-4892-a1f2-773c9d085bc5" />

  
## Test 1. Description: baseline connectivity

The goal of the baseline is to verify that the topology is up and running with the proper protocols and features.
The proceduer is as follows;

1.	Connect and configure the prototype network according to the Installation Checklist. 
2.	From PC1 and PC2 ping all of the other devices in the topology. Record any anomalies

## Test Results

| Test Case No | Description | Test Data | Expected Result | Actual Result | Pass/Fail | Defect No. | Defect Description |
|---|---|---|---|---|---|---|---|
| 1 | Test IP address has been configured on PC | Ipconfig /all | IP address: 192.168.1.2<br>Subnet mask: 255.255.255.0<br>Default gateway: 192.168.1.1<br>DNS: 192.168.0.254 | IP address: 192.168.1.2<br>Subnet mask: 255.255.255.0<br>Default gateway: 192.168.1.1<br>DNS: 192.168.0.254 | P |  |  |
| 2 | Carry out loop back test | Ping 127.0.0.1 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 3 | Test connectivity within local network | Ping 168.1.2 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 4 | Test connectivity with default gateway | Ping 192.168.1.1 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 6 | Test connectivity with default gateway on LAN 1 | Ping 192.168.0.1 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 7 | Test connectivity with default gateway on LAN 3 | Ping 192.168.2.1 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 8 | Test connectivity with PC on LAN 1 | Ping 192.168.0.3 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 9 | Test connectivity with PC on LAN 3 | Ping 192.168.2.3 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 10 | Test connectivity with server | Ping 192.168.0.254 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 11 | Test connectivity with printer | Ping 192.168.0.253 | 4 x replies in less than 1 sec | 4 x replies < 1 sec | P |  |  |
| 12 | Test login to server domain | Enter login details | Grants login access | Granted login access | P |  |  |
| 13 | Test printer by sending test print | Make print request | Prints paper | Printed paper | P |  |  |




