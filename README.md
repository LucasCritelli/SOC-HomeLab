# SOC Detection Lab - Professional Documentation
---
## Sumary
1. 
2.
3.
4.
5.
6.
7.
---
##Project Overview
This project is a fully isolated, virtualized Security Operations Center (SOC) Simulation Lab, designed to replicate real-world detection engineering, incident response, and threat hunting workflows. It integrates core SOC components:

✅ Network segmentation via pfSense ✅ Detection tooling (Wazuh, Snort) ✅ Security Management environment ✅ Target hosts for controlled attacks ✅ Adversary simulation for testing detection efficacy

Network Architecture
Virtualization Platform: VirtualBox with isolated VLAN configuration
pfSense Firewall: Central segmentation and traffic control
VLANs:
secmgmtvlan (192.168.20.0/24) - Security management tools (Wazuh, Kali Purple)
targetvlan (192.168.10.0/24) - Windows & Ubuntu hosts
attackvlan (192.168.30.0/24) - Adversary simulation machine (Parrot OS)
Optional: Security Onion integration for deep network visibility
Visual diagrams are provided in the folder.

