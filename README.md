**By Muhammad Balal Ansar (Cyber Security Expert)**

To create a professional project based on Nmap under the name "Network Map Scanner," you need to present it as a tool designed for network discovery and security auditing.

Below is a comprehensive description in English that you can use for your project documentation, README file, or presentation.

Project Overview: Network Map Scanner
1. Introduction
Network Map Scanner is a robust, command-line-based network exploration and security auditing tool. Built upon the powerful engine of Nmap (Network Mapper), this project provides a streamlined interface for network administrators, cybersecurity enthusiasts, and penetration testers to discover hosts, services, and vulnerabilities within a target network.

2. Key Features
Host Discovery: Efficiently identify active devices on a local or remote network.

Port Scanning: Determine which ports are open, closed, or filtered on target machines to map the attack surface.

Service Version Detection: Fingerprint running services (e.g., Apache, SSH, MySQL) to identify specific versions and potential weaknesses.

OS Detection: Analyze network packet responses to accurately predict the operating system of the target device.

Customizable Output: Generate clean, readable scan results in various formats for easy reporting and analysis.

3. How It Works
The Network Map Scanner acts as a wrapper around the Nmap binary, automating complex scanning tasks. By utilizing specific flags and scripts, it performs TCP connect scans, SYN stealth scans, and UDP scans to probe network infrastructure.

4. Use Cases
Network Inventory: Maintaining an accurate record of all devices currently connected to an enterprise network.

Security Auditing: Proactively identifying unauthorized devices or misconfigured services that could pose security risks.

Troubleshooting: Quickly verifying the connectivity and status of network services and firewall rules.

5. Technical Implementation
The tool leverages Nmap’s versatile scripting engine (NSE) to extend its capabilities. Whether performing a simple "Ping Sweep" or a comprehensive "Full Service Scan," the user inputs the target IP address range, and the scanner processes the raw data into actionable insights.

Basic Usage Instructions
To get started with your Network Map Scanner, you can use the following command structure:

For a Quick Discovery Scan:
network-map-scanner -sn [Target IP/Range]

For a Full Port & Service Scan:
network-map-scanner -sV -A [Target IP]

Important Disclaimer
Legal Notice: This tool is intended for educational purposes and authorized security testing only. Using this scanner against networks or systems without explicit permission from the owner is illegal and unethical. Always ensure you have written authorization before performing a network scan.
