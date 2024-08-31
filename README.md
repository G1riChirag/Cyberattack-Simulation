# Cyberattack Simulation

## Overview
This project was developed as part of a group assignment for the Computer Security class at DePauw University. We simulated a phishing attack in a controlled Kali Linux environment, using Ettercap for a man-in-the-middle attack and the Social Engineering Toolkit (SEToolkit) for website cloning. Our goal was to demonstrate how attackers can exploit network vulnerabilities, such as ARP and DNS spoofing, to redirect users to malicious websites and steal their credentials.

## Abstract
The project simulates a cyberattack designed to steal confidential information by tricking users into entering credentials on a cloned website. Using ARP spoofing, we positioned the attacker between the victim and the server, while DNS spoofing redirected the victim’s traffic to a fake website. The attack was executed within a Kali Linux environment using SEToolkit for phishing and Ettercap for network traffic interception. This simulation highlights the vulnerabilities that allow for credential theft and emphasizes the importance of robust network security practices.

## Design Document
The Design Document outlines the theoretical framework of the attack. It explains how ARP spoofing and DNS spoofing are used to intercept and manipulate user traffic. The document covers the objectives of the attack, including the analysis of network vulnerabilities, and discusses potential targets, like users in public Wi-Fi areas. Technologies such as Kali Linux, Ettercap, Wireshark, and HTML/CSS for website cloning are explained, alongside the general methodology for executing the attack. The document also highlights how phishing emails can be used to increase the effectiveness of the attack.

## Implementation Document
The Implementation Document details the step-by-step process followed during the project. It includes a discussion of deviations from the original design, such as the switch from Apache to SEToolkit for web hosting, and the decision to use Gmail login templates instead of Amazon. The document also addresses technical challenges, such as resolving IP conflicts within a virtual machine setup and troubleshooting issues with DNS spoofing. Screenshots and walkthroughs of the configuration processes are provided, along with a list of security controls against the demonstrated attack.

## Group Members
- Chirag
- Hayley
- Nam
- Tatsuki

