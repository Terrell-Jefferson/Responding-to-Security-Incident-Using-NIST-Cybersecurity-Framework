# Responding-to-Security-Incident-Using-NIST-Cybersecurity-Framework

# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Incident Report Analysis](#incident-report-analysis)

-------

# Introduction <a name="introduction">

A mock assessment of an ICMP-based DDoS attack using the NIST Cybersecurity Framework, completed as part of my cybersecurity portfolio and as part of Google's <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Cybersecurity Professional Certificate</a> on Coursera in the  <a href='https://www.coursera.org/learn/networks-and-network-security/home'> Connect and Protect: Networks and Network Security </a> Course .
   
The goal is to analyze a distributed denial-of-service (DDoS) incident and apply the NIST Cybersecurity Framework to strengthen the organization’s security posture. This exercise requires reviewing how an ICMP flood attack entered the internal network, evaluating gaps (like an unconfigured firewall), and ensuring to follow the Identify, Protect, Detect, Respond, and Recover functions when responding to the incident.

-------

# Scenario  <a name="scenario">
Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets

- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

- Network monitoring software to detect abnormal traffic patterns

- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:

- **Identify** security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

- **Protect** internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

- **Detect** potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

- **Respond** to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

- **Recover** affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

[Applying the NIST CSF .pdf](https://github.com/user-attachments/files/23733726/Applying.the.NIST.CSF.pdf)

-------

# Incident Report Analysis  <a name="incident-report-analysis">

**Summary:**

The company experienced a DDoS attack that overwhelmed the network with a flood of inbound ICMP packets. As a result, normal network traffic could not access internal resources and all services became unresponsive for two hours. The incident management team mitigated the disruption by blocking incoming ICMP packets, shutting down non-critical services, and restoring critical systems.

**Identify:**

A threat actor exploited an unconfigured firewall to deliver a distributed ICMP flood attack into the organization’s internal network. This affected the entire network by disrupting access to all internal services and resources. All critical systems required immediate protection and restoration to ensure operational stability.

**Protect:**

The cybersecurity team implemented firewall rules to limit incoming ICMP packet rates and an IDS/IPS system to filter ICMP traffic based on suspicious characteristics. These measures help reduce the likelihood that similar high-volume attacks will overwhelm the network in the future.

**Detect:**

To improve detection capabilities, the team configured source IP address verification on the firewall to identify spoofed IP addresses in ICMP traffic. They also deployed network monitoring software to track abnormal traffic patterns, enabling earlier identification of potential DDoS activity.

**Respond:**

For future incidents, the cybersecurity team will isolate impacted systems to contain the attack and prevent further disruption. They will focus on restoring critical network services first, reviewing network logs for indicators of malicious activity, and documenting the event. All significant incidents will be escalated to management and legal authorities when appropriate.

**Recover:**

To recover from an ICMP-based DDoS attack, the organization must restore network services to normal operation by first blocking external ICMP traffic at the firewall. Non-critical systems should remain offline to minimize load while critical resources are restored. Once the attack traffic subsides, remaining systems and services can be brought back online safely to resume full operational capacity.

-------

