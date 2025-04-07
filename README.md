#Connections Between Cloud, ISP, Firewall, Routers, and Layer-3 Switch

Network	Network Address
CLOUD Area	8.0.0.0/8
ISP1 – Internet	20.20.20.0/30
ISP2 – Internet	30.30.30.0/30
ISP1 – FWL1	105.100.50.0/30
ISP1 – FWL2	105.100.50.4/30
ISP2 – FWL1	205.200.100.0/30
ISP2 – FWL2	205.200.100.4/30

FWL1 to-MLSW1	10.2.2.0/30
FWL1 to-MLSW2	10.2.2.4/30
FWL2 to-MLSW1	10.2.2.8/30
FWL2 to-MLSW2	10.2.2.12/30

Cisco ASA Firewall
Cisco Adaptive Security Appliance (ASA) is a security device that combines firewall, VPN, and other network security services in a single platform. It provides advanced threat defense, intrusion prevention, 
and protects the network from attacks by monitoring, controlling, and filtering traffic. Key features include:
    - Stateful packet inspection
    - Virtual Private Network (VPN) support
    - Intrusion Prevention System (IPS)
    - Web filtering and malware defense
    - Secure access control and user authentication
