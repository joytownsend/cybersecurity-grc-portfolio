# Lab 2 — Protocol Identification

Author: Joy Townsend  
Date: March 7, 2026

## Objective

Identify which networking protocols are used for loading a website, sending email, streaming video, downloading files, and DNS lookups.

---

## Loading a Website

Protocols Used  
HTTPS  
DNS  
TCP  
IP

Explanation

When a user enters a website address in a browser, a DNS request first translates the domain name into an IP address. After the IP address is located, the browser uses HTTPS to request the webpage from the server. TCP ensures the data packets arrive correctly and in order, while IP handles addressing and routing across networks.

---

## Sending Email

Protocols Used  
SMTP  
TCP  
IP

Explanation

When sending an email, the device uses SMTP to transfer the message to a mail server. TCP ensures reliable transmission of the email data, and IP routes the data packets to the correct destination server.

---

## Streaming Video

Protocols Used  
TCP or UDP  
IP

Explanation

Streaming services send video data continuously across the network. TCP may be used when reliability is important, while UDP may be used when speed is more important than perfect packet delivery.

---

## Downloading Files

Protocols Used  
FTP  
HTTP or HTTPS  
TCP  
IP

Explanation

Files can be transferred using FTP or through HTTP or HTTPS downloads. TCP ensures reliable delivery of file packets.

---

## DNS Lookups

Protocols Used  
DNS  
UDP  
IP

Explanation

DNS translates domain names into IP addresses. DNS queries typically use UDP because it is faster and requires less overhead.
