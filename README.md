# Penetration Test and Report
## Final Project: Red Team, Blue Team and Network Analysis
This project consisted of monitoring a vulnerable network in Azure with an ELK Stack. Then attacking the network and analyzing the network traffic and alerts that were generated. And finally creating a presentation summarizing the attack and suggested system hardening.

### Step 1: Alerts were configured in Kibana
  * Excessive HTTP Errors
  * Request Size Monitor
  * CPU Usage Monitor

### Step 2: Attack Target
  * Use Nmap to scan for open port and services
  * Use wpscan to identify Word Press vulnerabilites
  * Use John the Ripper to crack a user hash; and password guessing
  * Obtain user shell via SSH
  * Obtain additional credentials in MySQL database
  * Obtain root privilege with sudo escalation using python command

### Step 3: View Alerts in Kibana
  * Nmap triggered alerts
  * wpscan triggered alerts

### Step 4: Generate and Present Final Report
  * Vulnerabilities Identified
  * Suggested System Hardening
  
