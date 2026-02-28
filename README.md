# kerberoasting_splunk_lab
Kerberoasting Attack Simulation with Detection in Active Directory using Splunk
This project demonstrates a real-world Kerberoasting attack simulation in an Active Directory environment and the detection of the attack using Splunk SIEM.

The objective is to emulate an attacker targeting Service Accounts within Active Directory and show how a Security Operations Center (SOC) can detect credential abuse through log analysis and threat hunting techniques.

This lab mirrors enterprise attack scenarios aligned with:

MITRE ATT&CK Framework

Blue Team Detection Engineering

SOC Monitoring Operations

Threat Hunting Methodology

Objectives

✅ Simulate Kerberoasting attack

✅ Capture authentication telemetry

✅ Forward Windows Security logs to Splunk

✅ Detect abnormal Kerberos Ticket activity

✅ Create SOC detection queries & alerts

✅ Map attack to MITRE ATT&CK

Detection Workflow

Attacker requests Kerberos tickets

Domain Controller logs Event 4769

Logs forwarded to Splunk

SPL query identifies anomaly

SOC analyst investigates

Alert generated

