# Simple SIEM Tool

A basic SIEM tool that processes and analyzes logs for potential security events, such as failed login attempts and port scans, and generates alerts.

## Features
- Analyzes logs for security events
- Detects failed login attempts and port scans
- Generates alerts for potential security incidents

## Requirements
- Python 3.x

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/D-MW/Simple-SIEM-Tool.git
   cd Simple-SIEM-Tool

**Explanation**

**Log File Paths:** Modify the AUTH_LOG and SYS_LOG variables to point to your actual log files.
**Thresholds: **Set thresholds for failed login attempts and port scans.
**Regex Patterns:** The script uses regex patterns to identify failed login attempts and suspicious connection attempts in the logs.
**Log Analysis Functions:** Functions analyze_log, detect_failed_logins, and detect_port_scans handle log analysis and alert generation.

