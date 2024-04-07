# Active-Directory-Project


# Objective

The primary goal of this lab was to conduct a comprehensive network analysis focusing on identifying and dissecting malicious activities within a given packet capture (PCAP) file. The lab aimed to enhance practical skills in traffic analysis, specifically in detecting web shell uploads, reconnaissance activities, and unauthorized remote command executions.

# Skills Learned

- Network configuration and management.
- Active Directory setup and user management.
- Brute force attack methods and their signatures.
- Event logging and monitoring.
- Usage of the MITRE ATT&CK Framework for understanding threat models.

# Tools Used

- VirtualBox for virtualization.
- Kali Linux for penetration testing.
- Windows Server 2022 and Windows 10 for setting up a target environment.
- Splunk for data aggregation and analysis.
- Hydra and Atomic Red Team for simulating attacks.

# Steps Taken
Day 1:
Created a logical diagram to visualize data flow and project structure.

Day 2:
Installed and configured all necessary virtual machines.
Configured virtual network settings to NAT-Network.
Set static IPs for machines to align with the logical diagram.
Installed Splunk on Ubuntu server and configured Splunk Universal Forwarder and Sysmon on the target machine and Windows Server.

Day 3:
Installed and configured Active Directory on the Windows Server and promoted it to a domain controller.
Created organizational units and users within Active Directory.
Configured the target machine to join the newly created domain.

Final Day:
Performed a brute force attack using Hydra instead of Crowbar.
Used Splunk to query for attack activity and analyzed the results.
Installed and configured Atomic Red Team to simulate attacks and generate telemetry.
Learned about Windows event codes and the MITRE ATT&CK Framework.

## Conclusion:
The lab provided hands-on experience in network traffic analysis, emphasizing the importance of being able to detect and understand the indicators of compromise and the tactics, techniques, and procedures (TTPs) used by attackers. The successful identification and analysis of the reconnaissance tools, the malicious file upload, and the subsequent remote command execution highlight the critical need for robust network monitoring and security measures.
