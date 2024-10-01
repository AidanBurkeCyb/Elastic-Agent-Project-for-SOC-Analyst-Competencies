# Elastic Agent Project for SOC Analyst Competencies

## Overview
This project demonstrates the use of Elastic Agent to monitor and analyse network traffic. I achieved this by installing Elastic Agent on a host running Kali Linux. I verified that Elastic Agent is ingesting data, created a dashboard to visualise the data, and configured an alert to simulate an adversary's network scanning behaviour using Nmap.

## Project Components

### Installation
- **Installed Elastic Agent** on a Kali Linux laptop to collect and centralise logs for analysis.

### Traffic Generation
- **Ran Nmap** to generate network traffic, simulating potential network scanning activities.

### Data Querying
- **Queried for Nmap events** in the Elastic SIEM to analyse the generated traffic and identify potential security threats.

### Dashboard Creation
- **Created a dashboard** within Elastic SIEM with:
  - **Vertical Axis:** Count of Nmap events
  - **Horizontal Axis:** Timestamps of when events occurred

### Alert Configuration
- **Configured an alert** to trigger when an Nmap scan is detected:
  - Trigger condition: When `process.name` is executed with the value `nmap` on a host device.
  - Action: Sends an email notification to alert about the potential scanning activity.

## Conclusion
This project showcases my ability to implement a security monitoring solution using Elastic Agent and demonstrates skills relevant to a SOC analyst role.
