# Linux Security Monitoring & Incident Detection using Splunk

This project implements a SOC-style security monitoring and detection solution for Linux systems using Splunk Cloud.

It focuses on identifying suspicious authentication activity, sudo misuse, unauthorized user creation, and correlated privilege escalation patterns through log analysis, dashboards, and alerts.

## Project Objectives
- Monitor Linux authentication and sudo activity
- Detect failed login and privilege escalation attempts
- Create alerts for high-risk security events
- Correlate multiple attack stages to reduce false positives
- Visualize security posture using SOC-style dashboards

## Environment
- Log Source: Linux authentication and system logs
- SIEM: Splunk Cloud (Free Trial)
- Dashboard Type: Splunk Dashboard Studio
- Testing Method: Simulated attack activity in a lab environment

## Key Detections
- Failed login attempts
- Failed sudo authentication
- Successful sudo activity
- New user account creation
- Correlated privilege escalation incidents

## Alerts
Alerts were configured and tested for:
- Failed sudo attempts
- New user creation
- Correlated multi-stage attack behavior

## Repository Structure
- `documentation/` – Detailed project report (PDF)
- `splunk-queries/` – SPL queries used for detections and correlation
- `dashboards/` – Dashboard screenshots
- `alerts/` – Alert trigger evidence

## Notes
This project was implemented in a controlled lab environment for learning
and validation purposes. It reflects SOC workflows such as log analysis,
alert validation, and incident correlation.
