# Windows Brute Force Detection & Investigation

## Overview

This project demonstrates the detection and investigation of potential
Windows brute-force activity using Splunk and Windows Security Event Logs.

The investigation focuses on repeated failed authentication attempts
represented by Windows Security Event ID 4625.

## Objectives

- Detect repeated failed Windows login attempts
- Analyze Windows Security Event ID 4625
- Identify patterns associated with potential brute-force activity
- Create a detection query in Splunk
- Configure a Splunk alert
- Investigate detected events
- Document the investigation findings

## Tools & Technologies

- Splunk
- Windows Security Event Logs
- Windows Event ID 4625
- SIEM

## Investigation Process

1. Collected Windows Security Event Logs
2. Searched for failed authentication events
3. Filtered Event ID 4625
4. Analyzed repeated failed login attempts
5. Created a Splunk detection query
6. Configured a Splunk alert
7. Investigated the detected events
8. Documented the findings

## Event ID 4625

Windows Security Event ID 4625 represents a failed account logon.

A single failed login does not necessarily indicate a brute-force attack.
Therefore, repeated failed authentication attempts were analyzed to
identify potential brute-force activity.

## Detection & Alerting

Splunk was used to search and analyze repeated Event ID 4625 events.
A detection query and alert were configured to identify suspicious
authentication patterns for further investigation.

## Investigation Findings

The investigation identified multiple failed authentication events.
The repeated login failures were analyzed as potential brute-force
activity based on the available log evidence.

## Evidence

Screenshots from the detection and investigation process are available
in the `screenshots` directory.

The investigation report is available in the `report` directory.

## Skills Demonstrated

- SIEM Monitoring
- Splunk Search
- Windows Event Log Analysis
- Event ID 4625 Analysis
- Brute-Force Detection
- Alert Configuration
- Security Monitoring
- Incident Investigation
- SOC Analysis

## Conclusion

This project demonstrates a basic SOC workflow for detecting and
investigating potential Windows brute-force activity using Splunk and
Windows Security Event Logs.
