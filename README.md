# SOC-Log-Analysis
# SOC Log Analysis: Brute-Force & Suspicious Login Detection

## Project Overview

This project simulates the role of a **Junior SOC Analyst** by analyzing authentication logs to detect brute-force attacks and suspicious login activity. The focus is on identifying abnormal patterns, investigating potential security incidents, and documenting findings in a SOC-style approach.

## Objectives

* Monitor and analyze authentication logs
* Detect brute-force and suspicious login attempts
* Correlate failed and successful login events
* Map findings to MITRE ATT&CK techniques

## Tools Used

* Splunk (SIEM)
* Authentication Logs (Linux/Windows – sample data)
* SPL (Search Processing Language)

## Detection Use Cases

* Multiple failed login attempts from the same IP
* Repeated login failures for a single user
* Login attempts outside normal business hours
* Failed login attempts followed by successful authentication

## MITRE ATT&CK Mapping

* **T1110 – Brute Force**

## Outcome

This project demonstrates core SOC Level-1 responsibilities such as log monitoring, alert investigation, threat identification, and incident documentation.

## Key Skills Demonstrated

* Security log analysis
* SIEM fundamentals
* Incident triage
* Threat detection
* SOC investigation workflow
