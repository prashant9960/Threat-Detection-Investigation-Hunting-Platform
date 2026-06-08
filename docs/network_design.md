# Network Design

## Assets

### WS-01

Role: Victim Workstation

### KALI-ATTACKER

Role: Adversary Machine

### SPLUNK

Role: SIEM Server

## Data Flow

KALI-ATTACKER
↓
WS-01
↓
Sysmon Logs
↓
Splunk
↓
Detection
↓
Investigation
↓
Threat Hunting
