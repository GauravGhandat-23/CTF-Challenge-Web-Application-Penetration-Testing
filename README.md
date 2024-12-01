# CTF Challenge: Web Application Penetration Testing

This repository contains resources and documentation for the **Capture the Flag (CTF) Challenge** completed as part of the Cyber Security and Ethical Hacking Internship Program. This challenge simulates real-world scenarios to identify and address vulnerabilities in a web application environment.

## Repository Title

**CTF Challenge: Secure the Flag**

---

## Overview

In this CTF, participants assume the role of an ethical hacker tasked with identifying vulnerabilities in a simulated web application. The exercise focuses on:

- Gaining hands-on experience with **web application penetration testing**.
- Developing skills in **manual vulnerability analysis** and **reconnaissance**.
- Utilizing industry-standard tools like **Burp Suite**, **dirb/dirbuster**, and others.

---

## Prerequisites

Before starting, ensure the following are in place:

- **Operating System**: Kali Linux (recommended)
- **Tools/Software**:  
  - VirtualBox  
  - Burp Suite  
  - dirb/dirbuster  
- **Skills/Knowledge**:  
  - Basic enumeration techniques  
  - Understanding of server services and web application structures  

---

## Goals

- Conduct **reconnaissance** on the deployed application.
- Perform **manual vulnerability analysis** to identify critical data points.
- Capture six hidden **flags** embedded in the vulnerable machine.

---

## Instructions

### 1. Environment Setup
1. Deploy the provided Virtual Machine Snapshot in **VirtualBox**.
2. Configure the network adapter to **Bridged Mode**.
3. Retrieve the appliance’s IP address.

### 2. Reconnaissance
1. Use the IP address to investigate and gather information about the application.
2. Identify Points of Interest (POI) and potential vulnerabilities.

### 3. Vulnerability Analysis and Flag Capture
1. **dirb**:  
   Use directory enumeration with `common.txt` to capture Flags 4 and 5.  
2. **Burp Suite**:  
   Analyze requests and responses to capture Flag 6.  
3. Other flags (1-3) should be identified through manual scanning and analysis.

---

## Tools and Techniques

- **Burp Suite**: For identifying vulnerabilities and analyzing responses.
- **dirb**: Directory enumeration using wordlists.
- **Manual Scanning**: Identifying POIs manually.

---

## Flags Captured

1. **Flag 1:** [Methodology to be documented]
2. **Flag 2:** [Methodology to be documented]
3. **Flag 3:** [Methodology to be documented]
4. **Flag 4:** Identified using `dirb` with a common wordlist.
5. **Flag 5:** Identified using `dirb` with a common wordlist.
6. **Flag 6:** Captured using **Burp Suite**.

---

## Disclaimer

This repository and associated activities are intended **strictly for educational purposes**. The tools and techniques demonstrated here should **only be used in authorized environments** with prior permission. The misuse of this information to target systems or applications without consent is illegal and unethical.


