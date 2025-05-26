# Elevate-1
# Network Reconnaissance Report - Task 1.1

 Overview

This project involves performing a basic network reconnaissance on a local subnet using Nmap, a powerful network scanning tool. The goal is to identify active devices, enumerate open ports and services, and assess potential security vulnerabilities.

---

Objectives

- Discover active IP addresses in the subnet
- Identify open ports and the associated services
- Evaluate potential security risks of exposed services
- Document and save the scan results in readable formats

---

## Tools Used

- **Nmap**: Network Mapper – used for scanning and service detection
- **Command Line Interface (CLI)**: To execute scans and commands

---

Steps Followed

1. **Network Scan with Nmap

The following command was used to scan the entire subnet (e.g., `192.168.1.1/24`) for active devices and open ports:

```bash
nmap -sS 192.168.1.1/24
