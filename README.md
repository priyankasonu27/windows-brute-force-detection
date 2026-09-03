*Windows Brute Force Detection & Investigation*

Overview

This project demonstrates the detection and investigation of potential
Windows brute-force activity using Splunk and Windows Security Event Logs.

The investigation focuses on repeated failed authentication attempts
represented by Windows Security Event ID 4625.

Objective

The main objectives of this project are:

- Detect repeated failed Windows login attempts
- Analyze Windows Security Event ID 4625
- Identify patterns associated with potential brute-force activity
- Create a detection query in Splunk
- Configure a Splunk alert
- Investigate the detected events
- Document the investigation findings

Tools & Technologies

- Splunk
- Windows Security Event Logs
- Windows Event ID 4625
- SIEM
- Windows

Detection Methodology

The investigation followed these steps:

1. Collected Windows Security Event Logs
2. Searched for failed authentication events
3. Filtered Windows Event ID 4625
4. Analyzed repeated failed login attempts
5. Created a Splunk detection query
6. Configured an alert for suspicious login activity
7. Investigated the resulting events
8. Documented the findings

Windows Event ID 4625

Event ID 4625 represents a failed account logon in Windows.

A single failed login attempt does not necessarily indicate a
brute-force attack. Therefore, repeated failed authentication attempts
were analyzed to identify potential brute-force behavior.

Splunk Detection

The Splunk search was used to identify repeated Event ID 4625 occurrences
within the available Windows security logs.

The detection focused on:

- Failed authentication attempts
- Source information
- Target account
- Logon type
- Event timestamp
- Frequency of failed attempts

Alert Configuration

A Splunk alert was configured to identify potential brute-force activity
based on repeated failed authentication events.

The alert was designed to help a SOC analyst identify suspicious
authentication patterns for further investigation.

Investigation Findings

The investigation identified multiple Windows Event ID 4625 events
representing failed authentication attempts.

The repeated failures were analyzed as potential brute-force activity,
rather than treating every failed login as a confirmed attack.

Evidence

Screenshots and investigation evidence are provided in the
`screenshots` directory.

The investigation report is available in the `report` directory.

Skills Demonstrated

- SIEM Monitoring
- Splunk Search & Investigation
- Windows Event Log Analysis
- Event ID 4625 Analysis
- Brute-Force Detection
- Alert Configuration
- Security Monitoring
- Incident Investigation
- SOC Analysis

Conclusion

This project demonstrates a basic SOC workflow for detecting and
investigating potential Windows brute-force activity using Splunk and
Windows Security Event Logs.
