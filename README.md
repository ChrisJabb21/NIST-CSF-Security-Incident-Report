# NIST-CSF-Security-Incident-Report

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Objective](#objective)
4. [Incident Report Analysis](#incident_report_analysis)
5. [Notes](#notes)
6. [Reflections](#reflections) 


# Introduction <a name="introduction"> 
A mock security incident report done as part of Cybersecurity documentation portfolio and [Google's Coursera Cybersecurity Certificate](https://www.coursera.org/google-certificates/cybersecurity-certificate) as part of the [Connect and Protect: Networks and Network Security course](https://www.coursera.org/learn/networks-and-network-security/home/week/1) to gain an understanding of network-level vulnerabilities and how to secure networks.

# Scenario <a name="scenario"> 
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets

- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

- Network monitoring software to detect abnormal traffic patterns

- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics


# Objective  <a name="objective"> 
You are tasked with using this security event to create a plan to improve your company’s network security, following _the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF_). 

The different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy align with NIST's CSF's five core functions:

- **Identify** security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

- **Protect** internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

- **Detect** potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

- **Respond** to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

- **Recover** affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.

# Incident Report Analysis <a name="incident_report_analysis"> 

## Summary
A security incident occcured where the organization’s internal network experienced a distributed denial of service (DDoS) attack. During the attack, the organization’s network services suddenly stopped responding. Devices on the internet network were affected and network resources within the affected network could not be accessed.

| Phase  | Description of what happened at each NIST CSF phase |
| --- | --- |
| Identify | The cybersecurity team investigated the security event and discovered a malicious actor had sent a flood of ICMP Pings into the company’s network through an unconfigured firewall. This vulnerability of the misconfigured firewall allowed the attacker to overwhelm the company’s network through a DDoS attack. |
| Protect | To protect and safeguard against future DDoS attacks, the network security team implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to be able filter out some ICMP traffic to the internal network based on suspicious characteristics. |
| Detect | To detect new and similar unauthorized network intrusions and improve the ability to detect these threats, the security team will install network monitoring software to detect abnormal traffic patterns and Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets. |
| Respond | The incident management team responded by blocking incoming ICMP packets, stopping all and bring non-critical network functionality offline, and restoring critical network services to contain the issue and begin identifying the root cause.Training for security personnels on this tool and updates to incident response playbooks for the Detect and Protect phases should be implemented to any existing documentation to improve response procedures. Management will have to promptly inform law enforcement of the DDoS incident depending on the affected organization’s industry based on the impact for the outage. (example: reporting the DDoS issue to a local FBI Field Office) |
| Recover | This attack took the network down for two hours and the IT and Security operation teams worked jointly to bring the network back online for normal business operations while the internal network was down for 2 hours. The cybersecurity team informed staff of what is going on and held a lessons learned session to present the root cause behind this attack as well as safeguards that will need to implemented to protect against future attacks. Being able to respond and recover faster then the 2 hours will be looked into and assessed after the safeguards in the protect and detect phases are implemented. Consideration of Cyber Insurance provider to help with recovery and consultation advice will need to be taken as well to try counter revenue loss. Next, an investigation will be conducted for legal actions pertaining to this cyberattack and determining the person(s) responsible for the attack and take it from there  to assess the extent of the damage caused by the cyberattack. |


# Notes <a name="notes"> 

This was a challenging exercise that I did really well initially. The part I struggled with was including too much and more detail then the exemplar example for this assignment and making sure my written doucmentation read fluidly to explain and break down each process. Nevertheless I was super close to matching the Exemplar example.
A consideration worth noting was scheduling a penetration testing exercise to evaluate and see if the security posture of the organization is improved and the safeguards are working properly. It is always better to be safe and test security then be sorry at the event of a breach.

[The Understanding and Responding to Distributed Denial-of-Service Attacks whitepaper published by the CISA.](https://www.cisa.gov/sites/default/files/publications/understanding-and-responding-to-ddos-attacks_508c.pdf)


NIST article on suggestions for the properly recovering from a cyberattack
[How to Recover from a Cyber Attack | NIST](https://www.nist.gov/blogs/manufacturing-innovation-blog/how-recover-cyber-attack#:~:text=Consider%20Cyber%20Insurance%20for%20Increased%20Recovery%20Capability%20Like,assist%20in%20identifying%20the%20extent%20of%20damage%20caused)

# Reflections <a name="reflections"> 
This was a challenging exercise that I did really well initially. The part I struggled with was including too much and more detail then the exemplar example for this assignment and making sure my written doucmentation read fluidly to explain and break down each process. Nevertheless, I was super close to matching the Exemplar example.
