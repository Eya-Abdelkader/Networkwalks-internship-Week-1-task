# Cybersecurity & Pentesting Lab Setup

Week 1 project from the Cybersecurity program at **Networkwalks** ([your batch]).

This repository documents how I built an isolated virtual cybersecurity testing lab using **VirtualBox** and **Kali Linux**, along with the extra **Wireshark** labs I completed.

---

## Overview

The goal of this project was to create a safe, private environment for practicing networking and security skills. The lab runs entirely inside virtual machines on a private NAT Network, so it stays separated from my main system and home network.

## Tools Used

- VirtualBox
- Kali Linux
- Wireshark
- Git & GitHub

## What I Completed

- [x] Installed and configured VirtualBox
- [x] Imported and configured Kali Linux
- [x] Created a private NAT Network
- [x] Configured and verified Kali network settings
- [x] Tested network connectivity and DNS resolution
- [x] Created a clean VM snapshot for recovery

## Lab Setup Steps

### 1. Install VirtualBox
Downloaded and installed VirtualBox, then confirmed it was working correctly.

### 2. Import and Configure Kali Linux
Imported the Kali Linux virtual machine into VirtualBox and adjusted its settings.

### 3. Create a Private NAT Network
Created a NAT Network in VirtualBox so lab machines can talk to each other and reach the internet while staying isolated from the host network.

### 4. Configure and Verify Network Settings
Attached Kali to the NAT Network and verified its IP configuration.

### 5. Test Connectivity and DNS Resolution
Tested that the VM had working connectivity and could resolve domain names.

### 6. Create a Clean Snapshot
Took a snapshot of the working setup so I can quickly restore it if something breaks.

---

## Bonus: Wireshark Labs

I completed all of the extra Wireshark projects. They helped me learn how to extract important information from network traffic.

| # | Lab |
|---|-----|
| 1 | [Lab 1 name] |
| 2 | [Lab 2 name] |
| 3 | [Lab 3 name] |
| 4 | [Lab 4 name] |

---

## What I Learned

- Virtual machine networking
- NAT vs. NAT Network
- IP configuration
- Using snapshots for backup and recovery
- Extracting important information from network traffic with Wireshark
- Documenting technical work clearly

## Acknowledgements

Thanks to [Mentor name] and the Networkwalks team for the guidance and support.

---

*Looking forward to Week 2!*
