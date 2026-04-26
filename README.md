# Flask-based-Supply-Chain-Attack-Simulator

# Overview
The Supply Chain Attack Simulator is a cybersecurity project developed using Python and Flask to demonstrate how attackers can compromise software updates during the distribution process and how security mechanisms can detect such threats in real time. It recreates a software supply chain environment where a legitimate update is managed by a vendor, while an attacker attempts to tamper with it by injecting malicious content.

This project highlights the importance of protecting software delivery channels, as many organizations rely on third-party vendors, external packages, and regular updates.

# Objective

The main objective of this project is to simulate a real-world software supply chain attack and implement defensive measures that help users identify whether an update file is safe or compromised.

The system classifies updates into three categories:
1. Trusted – The file is authentic and unchanged
2. Compromised – The file has been modified or infected
3. Untrusted – The file is not verified by the trusted source

# Features
1. Real-time monitoring dashboard
2. Simulation of vendor software signing
3. Simulation of malware injection attacks
4. File integrity verification
5. Digital signature authentication
6. Automatic trust status detection
7. Interactive web-based interface
8. Educational cybersecurity demonstration

## Technologies Used
Python
Flask
HTML
CSS
File Hashing
Digital Signature Concepts

## How the Project Works
A vendor provides a legitimate software update and marks it as trusted. The simulator then allows an attacker to modify the update file by adding malicious content. Once the file is changed, the system detects the tampering through integrity and signature checks.

Based on the results, the dashboard displays whether the update is trusted, compromised, or untrusted.

## Real-World Relevance
This project reflects real cyberattacks where hackers target software vendors or update systems to spread malware. Similar incidents have affected major organizations worldwide.

### It helps users understand the risks of:
1. Fake software updates
2. Compromised vendor packages
3. Third-party dependency attacks
4. Malicious update distribution

## Applications
1. Cybersecurity learning and awareness
2. College academic projects
3. Demonstration in seminars and workshops
4. Security training environments
5. Ethical hacking labs

## Future Enhancements
1. Advanced encryption-based signatures
2. Email alerts for attacks
3. Automatic quarantine of infected files
4. Activity logs and reports
5.Cloud-based monitoring dashboard
6. Multi-user admin support

## Conclusion
The Supply Chain Attack Simulator is a practical and educational project that demonstrates how software updates can become attack vectors and how security controls can defend against them. It provides hands-on understanding of modern supply chain threats in a simple and interactive way.
