# Lab 5 — Firewall Rules

Author: Joy Townsend  
Date: March 7, 2026

## Objective

Create example firewall rules and explain how each rule helps protect a network from unauthorized access and security threats.

Firewalls monitor and control incoming and outgoing network traffic based on predefined security rules. These rules determine whether traffic should be allowed or blocked.

## Firewall Rule 1 — Allow Secure Web Traffic

Rule  
Allow inbound and outbound HTTPS traffic on port 443.

Purpose  
This rule allows secure communication between users and websites. HTTPS encrypts data transmitted between a web browser and a server, protecting sensitive information such as login credentials and personal data.

Result  
Users can securely access websites while maintaining encrypted communication.

---

## Firewall Rule 2 — Block Telnet Traffic

Rule  
Block inbound and outbound traffic on port 23.

Purpose  
Telnet is an outdated protocol that sends data in plain text without encryption. Blocking Telnet prevents attackers from intercepting login credentials and sensitive data.

Result  
Prevents the use of insecure remote access protocols on the network.

---

## Firewall Rule 3 — Allow DNS Requests

Rule  
Allow outbound DNS traffic on port 53.

Purpose  
DNS is required to translate domain names into IP addresses. Allowing DNS traffic enables users to access websites and network services.

Result  
Devices can resolve domain names and communicate with internet services.

---

## Firewall Rule 4 — Block Unauthorized Incoming Connections

Rule  
Block all inbound traffic that is not part of an established or trusted connection.

Purpose  
This rule prevents external systems from initiating unauthorized connections to devices inside the network.

Result  
Protects internal devices from unauthorized access attempts and potential attacks.

---

## Firewall Rule 5 — Allow Internal Network Communication

Rule  
Allow traffic between trusted devices within the internal network.

Purpose  
Devices inside the same network often need to communicate with each other to share files, printers, and other resources.

Result  
Ensures internal network functionality while still protecting the network perimeter.

---

## Explanation

Firewall rules help enforce network security policies by controlling which traffic is allowed or denied. By allowing secure services such as HTTPS and DNS while blocking insecure protocols like Telnet, firewall rules help reduce the risk of unauthorized access, data interception, and network attacks.

Proper firewall configuration is an essential component of network security and is widely used in enterprise environments to protect systems and sensitive data.
