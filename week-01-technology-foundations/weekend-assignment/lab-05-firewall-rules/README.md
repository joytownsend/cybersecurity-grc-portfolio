# Lab 5 — Firewall Rules

Author: Joy Townsend  
Date: March 7, 2026

## Objective

Create five example firewall rules and explain what each rule accomplishes.

Firewalls monitor and control incoming and outgoing network traffic based on security rules. These rules determine whether traffic is allowed or blocked.

## Firewall Rule 1 — Allow Secure Web Traffic

Rule  
Allow outbound HTTPS traffic on port 443.

Explanation  
HTTPS is used for secure web browsing. Allowing this traffic enables users to access secure websites while keeping communication encrypted.

---

## Firewall Rule 2 — Block Telnet

Rule  
Block inbound and outbound traffic on port 23.

Explanation  
Telnet transmits data in plain text and is considered insecure. Blocking this protocol prevents attackers from capturing login credentials or sensitive information.

---

## Firewall Rule 3 — Allow DNS Requests

Rule  
Allow outbound DNS traffic on port 53.

Explanation  
DNS is required for translating domain names into IP addresses. Without DNS, users would not be able to reach websites using domain names.

---

## Firewall Rule 4 — Block Unknown Incoming Traffic

Rule  
Block all inbound traffic that is not associated with an established connection.

Explanation  
This rule prevents external systems from initiating unauthorized connections to devices inside the network.

---

## Firewall Rule 5 — Allow Internal Network Communication

Rule  
Allow traffic between devices inside the local network.

Explanation  
Devices on the same network often need to communicate with each other to share resources such as files, printers, and internal services.

## Summary

Firewall rules protect networks by allowing trusted traffic and blocking suspicious or unnecessary connections. Proper firewall configuration reduces the risk of unauthorized access and improves overall network security.
