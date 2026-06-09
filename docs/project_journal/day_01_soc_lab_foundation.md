# Project Journal

## Day 1 - SOC Lab Foundation

Date: June 8, 2026

### Objectives

Build the foundational infrastructure for the Threat Detection, Investigation & Hunting Platform.

### Completed Tasks

#### Infrastructure Deployment

* Created GitHub repository
* Created project folder structure
* Installed Windows 11 VM (WS-01)
* Configured Kali Linux attacker machine
* Installed Ubuntu Server VM (SPLUNK)

#### Network Configuration

* Configured NAT networking
* Assigned IP addresses
* Validated connectivity between systems
* Troubleshot Windows Firewall ICMP restrictions

#### SIEM Deployment

* Installed Splunk Enterprise
* Configured administrative account
* Verified Splunk services
* Verified Splunk Web availability

#### Documentation

* Architecture documentation
* Asset inventory
* Network design
* Network validation
* SIEM architecture
* Splunk installation guide

### Final Infrastructure

| Asset         | Role               | IP Address     |
| ------------- | ------------------ | -------------- |
| WS-01         | Victim Workstation | 192.168.44.155 |
| KALI-ATTACKER | Adversary Machine  | 192.168.44.131 |
| SPLUNK        | SIEM Server        | 192.168.44.157 |

### Lessons Learned

* VMware NAT networking
* Linux network troubleshooting
* Windows Firewall behavior
* Ubuntu Server administration
* Splunk Enterprise deployment
* SOC lab architecture design

### Next Objectives

* Install Sysmon on WS-01
* Install Splunk Universal Forwarder
* Ingest Windows logs into Splunk
* Validate telemetry collection

### Status

Day 1 Completed Successfully
