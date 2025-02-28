EIGRP Packet Tracer Project

📌 Overview

This project demonstrates the implementation of EIGRP (Enhanced Interior Gateway Routing Protocol) in Cisco Packet Tracer. The topology consists of multiple routers, switches, and PCs, configured to communicate dynamically using EIGRP.

📁 Project Files

EIGRP_PacketTracer.pkt → Cisco Packet Tracer file with the full network setup.

eigrp_configuration.txt → Command-line configurations for all routers.

⚙️ Network Topology

The network consists of:

3 Routers (R1, R2, R3)

3 Switches (Switch0, Switch1, Switch2)

3 PCs (PC0, PC1, PC2)

Configured using EIGRP for dynamic routing

🛠 EIGRP Configuration Commands

Below are the essential commands used to configure EIGRP on the routers:

Router R1

configure terminal
router eigrp 100
network 192.168.1.0 0.0.0.255
network 10.0.0.0 0.0.0.255
no auto-summary
exit

Router R2

configure terminal
router eigrp 100
network 10.0.0.0 0.0.0.255
network 172.16.0.0 0.0.0.255
no auto-summary
exit

Router R3

configure terminal
router eigrp 100
network 172.16.0.0 0.0.0.255
network 192.168.2.0 0.0.0.255
no auto-summary
exit

🚀 Steps to Run the Project

Download Cisco Packet Tracer if not already installed.

Open the EIGRP_PacketTracer.pkt file in Packet Tracer.

Verify connectivity using ping commands.

Test routing using show ip route and show ip eigrp neighbors.

🔥 Key Features

EIGRP Dynamic Routing for fast convergence.

Efficient resource utilization by reducing manual route entries.

Improved scalability compared to static routing.

Packet loss prevention through redundancy in the topology.

📌 Future Improvements

Implement Access Control Lists (ACLs) for security.

Configure QoS (Quality of Service) for better network performance.

Expand topology to include WAN connections.

📝 Author

Jatin ChoudharyFeel free to reach out for discussions or improvements! 🚀
