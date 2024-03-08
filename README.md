# Network Design for Omalies Coffee Shop

## Overview

The network design for Omalies Coffee Shop is engineered to provide robust connectivity, security, and reliability to support its operations. The design incorporates:
- pfSense firewall ***configured with dual WAN for failover***
- 24-port Cisco 2960 switch ***configured to manage network traffic***
### High Level overview:

![ocs_network](/Omalies/assets/ocs_network.png)

### pfSense Firewall:

![pfsense_firewall](/Omalies/assets/pfsenses_firewall.png)

- **Functionality**: Acts as the primary gateway and firewall for the network, ensuring secure traffic flow and protecting against external threats.
- **Features**:
  - Dual WAN Configuration: Provides redundancy and automatic failover in case of internet connection failure.
  - Stateful Packet Inspection (SPI): Monitors and filters network traffic based on predefined rules, enhancing security.
  - VPN Support: Enables secure remote access for authorized users.
  - Traffic Shaping: Optimizes bandwidth utilization for different types of traffic, prioritizing critical applications.

### Cisco Switch:

![Cisco](/Omalies/assets/cisco1.png)

- **Functionality**: Serves as the central point of connectivity for devices within the network, facilitating efficient data transfer and network management.
- **Features**:
  - 24 Ports: Provides ample connectivity for wired devices such as computers, printers, POS terminals, and VoIP phones.
  - VLAN Support: Segments the network into virtual LANs to improve performance, security, and manageability.
  - Quality of Service (QoS): Prioritizes network traffic based on predefined criteria, ensuring optimal performance for critical applications like VoIP.
  - Layer 2 Switching: Enables fast and efficient data forwarding within the local network.

## Network Topology:
![ocs](/Omalies/assets/ocs_network_task.png)

## Benefits:

- **High Availability**: Dual WAN configuration ensures uninterrupted internet connectivity even in case of ISP failures.
- **Enhanced Security**: pfSense firewall with SPI protects the network from external threats, ensuring data integrity and confidentiality.
- **Efficient Traffic Management**: Traffic shaping and QoS features optimize bandwidth utilization, ensuring a smooth and responsive network experience.
- **Scalability**: The network design can accommodate future growth and expansion of Omalies Coffee Shop without significant modifications.

## Conclusion:

The network design incorporating pfSense firewall with dual WAN failover and Cisco 2960 switch provides Omalies Coffee Shop with a reliable, secure, and efficient network infrastructure. It ensures uninterrupted connectivity, robust security, and efficient traffic management, thereby supporting the seamless operation of the business.

### 🧰 **Tools:**

<img align="left" alt="Linux" width="80px" style="padding-right:40px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
<img align="left" alt="Python" width="80px" style="padding-right:40px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="GitHub" width="80px" style="padding-right:40px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
<img align="left" alt="Bash" width="80px" style="padding-right:40px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
<img align="left" alt="Docker" width="80px" style="padding-right:40px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
<img align="left" alt="AWS" width="80px" style="padding-right:40px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" />
<img align="left" alt="YAML" width="80px" style="padding-right:40px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/yaml/yaml-original.svg" />
<img align="left" alt="Cisco" width="80px" style="padding-right:40px;" src="/Omalies/assets/cisco1.png" />


<br />

<hr>
