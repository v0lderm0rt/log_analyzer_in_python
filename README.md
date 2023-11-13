# Firewall Log Analysis Script

## Overview

This script is designed to analyze firewall logs, focusing on entries with the "ALLOW" action. It extracts information such as source/destination IP addresses and source/destination ports from the logs, counts the occurrences, and generates a report with insights into the most active IP addresses and ports for allowed connections.

## Usage

1. **Clone the Repository:**
   in bash -
   git clone https://github.com/v0lderm0rt/log_analyzer_in_python.git
   cd firewall-log-analysis
2. **Run the script:**
   use the following command to run the script--
   python firewall_log_analysis.py
3. **View the report**
   After running the script, a report will be generated and saved in a file named "firewall_analysis_report.txt."
