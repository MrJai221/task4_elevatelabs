# Task 4: Firewall Setup and Use on Windows/Linux

This repository documents the process of setting up and configuring basic firewall rules on both Windows and Linux operating systems as part of a networking and security learning task.

## Objective

The main goal of this task is to configure and test basic firewall rules to either allow or block network traffic, thereby gaining fundamental skills in firewall management and understanding network traffic filtering.

## Tools Used

*   **Windows:** Windows Defender Firewall with Advanced Security
*   **Linux:** UFW (Uncomplicated Firewall)

## Project Overview

This project demonstrates the essential steps to secure a system at the network level using host-based firewalls. The configurations are designed to follow a security best practice of "default deny" for incoming traffic while allowing necessary services.

### Windows Firewall Configuration

-   Accessed **Windows Firewall with Advanced Security** (`wf.msc`).
-   Created an **inbound rule** to block traffic on a specific port (e.g., RDP on port 3389).
-   Created an **outbound rule** to allow a specific application to access the network.
-   Tested the rules to verify their effectiveness.
-   Exported the firewall policy for backup and documentation.

### Linux (UFW) Firewall Configuration

-   Installed and enabled **UFW** on an Ubuntu/Debian-based system.
-   Set the default policies to **deny incoming** and **allow outgoing** traffic.
-   Added rules to **allow essential services** like SSH (port 22), HTTP (port 80), and HTTPS (port 443).
-   Added a rule to **block a specific port**.
-   Verified the firewall status and rules using `sudo ufw status verbose`.

## Deliverables

-   **Configuration Files/Screenshots:** This repository may contain screenshots of the firewall rules or the exported policy file for Windows and the command-line output for UFW.
-   **Report:** A detailed report outlining the setup procedure, testing methods, and outcomes for both operating systems is included in `Firewall_Report.txt`.

## Outcome

This exercise provides hands-on experience with fundamental security practices. Key takeaways include:

-   Understanding the difference between inbound and outbound traffic.
-   The importance of a "default deny" inbound policy.
-   How to create rules based on ports, protocols, and applications.
-   Methods for testing and verifying firewall rules.

This project serves as a practical guide for basic firewall management on two of the most common operating systems.
