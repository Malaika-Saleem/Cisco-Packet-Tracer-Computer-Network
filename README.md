# Computer Networks Project

## Overview
This project involves designing, configuring, and simulating a complex multi-protocol network topology using Cisco Packet Tracer Instructor Version. You will work with a given network design and minimal documentation, applying subnetting, routing protocols, NAT, DHCP, and access control to meet specific requirements.

## Important Notes
- **Academic Integrity:**  
  Do **not** copy or cheat. Strict evaluation criteria will penalize dishonest work with zero marks.  
  Your own efforts and understanding will be highly valued.

- **Tools:**  
  Use **Cisco Packet Tracer Instructor Version** to simulate and test the network.

- **Documentation:**  
  Minimal technical documentation is provided; you must interpret and build the network yourself.

## Project Tasks

1. **IP Addressing & Subnetting**  
   - Use the unique IP address allocation file provided.  
   - Identify your assigned IP block and the required number of hosts per subnet.  
   - Apply **Variable Length Subnet Masking (VLSM)** for all subnets.  
   - For inter-router links, allocate 4 IP addresses per link (including network and broadcast).

2. **Routing**  
   - Use the specified routing protocols indicated on each network block (EIGRP, OSPF Area 1, OSPF Area 2, RIP).  
   - Perform **Route Redistribution** on routers connecting different routing protocol blocks.

3. **DHCP Configuration**  
   - Configure DHCP servers located in the last block of the topology.  
   - Hosts in all routing protocol areas (EIGRP, OSPF, RIP) must receive IP addresses dynamically from DHCP.

4. **Network Address Translation (NAT)**  
   - Implement NAT on:  
     - Router20 (Network J)  
     - Router8 (Network E)  
   - Use the assigned private IP addresses provided in the IP addressing file for NAT.

5. **Access Control Lists (ACLs)**  
   - Restrict web server access as follows:  
     - One PC in Network A denied web access.  
     - One smartphone each in Networks E and J denied web access.  
     - All hosts in Network D denied web access.  
   - Apply ACLs on the router connected to the web server to enforce these rules.

6. **Mail Server Configuration**  
   - A mail server exists in the first network block.  
   - Configure email settings on all hosts to send and receive emails internally.  
   - Explore and apply necessary configurations independently.

## Deliverables
- Fully configured Cisco Packet Tracer simulation file (.pkt) implementing all requirements.  
- Optional documentation summarizing addressing, routing, ACLs, NAT, and mail configurations.  
- Demonstration of network connectivity, DHCP functionality, NAT operation, ACL enforcement, and mail server communication.

## Tips and Reminders
- Analyze the IP addressing file carefully for your assignments.  
- Use subnet calculators or manual VLSM for optimized IP usage.  
- Test network connectivity incrementally.  
- Document your configuration steps clearly.  
- Avoid shortcuts; understanding is crucial.

## Tools & Resources
- Cisco Packet Tracer Instructor Version (required)  
- IP Addressing and host requirement file (provided)  
- Cisco IOS command references for routing, ACL, NAT, DHCP, and mail services

## Academic Integrity Warning
**Any form of copying, plagiarism, or unauthorized collaboration will result in an automatic zero.**  
Ensure all work is your own.

---

If you need assistance or clarifications, feel free to reach out. Good luck and enjoy building the network!
