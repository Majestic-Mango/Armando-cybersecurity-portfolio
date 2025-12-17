# Armando-cybersecurity-portfolio
Hands-on cybersecurity and pentesting projects demonstrating offensive and defensive security skills.
# Armando Monarrez – Cybersecurity Portfolio

Veteran cybersecurity professional with a background in U.S. Air Force Security Forces. 
This repository showcases hands-on cybersecurity and pentesting projects focused on 
network reconnaissance, vulnerability assessment, traffic analysis, and defensive mitigation.

## Skills Overview
- Network reconnaissance and service enumeration
- Vulnerability assessment and risk analysis
- Packet capture and traffic analysis
- TCP/IP and networking fundamentals

## Tools
- Nmap
- Wireshark
- VMware
- Cisco Packet Tracer
- Angry IP Scanner

## Projects
Projects will be added here as they are completed.

## Executive Summary

This portfolio documents a structured security assessment conducted within a
controlled lab environment, demonstrating a complete workflow from discovery
and enumeration to exploitation and defensive remediation.

Initial reconnaissance identified a Linux-based host exposing multiple legacy
network services with weak or absent authentication controls. Service
enumeration revealed anonymous access to SMB and FTP services, as well as the
presence of unnecessary network services contributing to an expanded attack
surface.

A controlled exploitation was performed against an exposed FTP service running
vsFTPd version 2.3.4, a version known to contain a backdoored authentication
mechanism. Exploitation resulted in root-level access, validating the severity
of the identified misconfiguration. Exploitation activities were intentionally
limited in scope and terminated immediately following access verification.

Following exploitation, a defensive hardening analysis was conducted to
demonstrate how the identified risks could be mitigated in an enterprise
environment. Recommended controls focused on service removal, authentication
enforcement, network segmentation, and alignment with industry standards such
as the CIS Benchmarks and the NIST Cybersecurity Framework.

Collectively, these projects demonstrate the ability to assess system exposure,
validate real-world impact, and translate technical findings into actionable
security improvements while maintaining ethical boundaries and professional
reporting standards.
