# SOHO-Network-Security-Cisco
# Secure SOHO Network Implementation and Port Security

**Platform:** Cisco Packet Tracer  
**Project Type:** Networking and Basic Network Security Lab

## 1. Objective
Design and test a small SOHO network, configure DHCP, implement switch Port Security, and verify connectivity and basic security controls.

## 2. Network Components
- 1 Cisco 1941 Router
- 1 Cisco 2960 Switch
- 3 PCs and 1 Laptop

## 3. DHCP Configuration
Configured a DHCP pool named `SOHO_Network` for `192.168.1.0/24`.

- Default gateway: `192.168.1.1`
- DNS server: `8.8.8.8`
- Excluded addresses: `192.168.1.1–192.168.1.10`

*Note: Router interface addressing and DHCP leases require separate verification.*

## 4. Port Security
Configured switch Port Security to limit secure MAC addresses on access ports.

- Maximum secure MAC addresses: 1
- Violation mode: Restrict
- Sticky MAC learning: confirmed on `Fa0/1`

The available screenshot showed zero violations at capture time; this does not establish the result of an earlier test.

## 5. Testing and Troubleshooting
Completed:
- Connectivity and ping testing
- Port Security and violation testing
- Interface troubleshooting and reset
- Saving the final Packet Tracer configuration

## 6. Conclusion
This lab demonstrates basic network design, DHCP configuration, Port Security, and troubleshooting. It provides a foundation for future VLAN, network monitoring, and SOC-related projects.

*This is a learning simulation, not a complete production security solution.* 
<img width="960" height="1020" alt="Screenshot 2026-10-11 225108" src="https://github.com/user-attachments/assets/8e181e9a-5e08-4e1c-a695-dc1b76975a65" /> 
<img width="960" height="917" alt="Screenshot 2026-10-11 225308" src="https://github.com/user-attachments/assets/b04ba240-4bee-47aa-b354-f13a29591432" />
<img width="960" height="917" alt="Screenshot 2026-10-11 225750" src="https://github.com/user-attachments/assets/67700454-38a9-417c-86d1-6dbdb97e47cd" />


