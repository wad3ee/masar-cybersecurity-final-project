# Masar Final Project – Cybersecurity

## About the Project

This project was completed as part of the Masar training program. 
The main goal was to test common web application vulnerabilities, 
understand how they work, and apply fixes to make the application more secure.

We tested the vulnerabilities in a lab environment and checked the 
application again after applying the fixes.

## Vulnerabilities Tested

- SQL Injection
- OS Command Injection
- Cross-Site Scripting (XSS)
- File Upload Vulnerability

## Defensive Security

We also worked on the defensive side of the project, including:

- Analyzing Apache logs and Bash history.
- Reconstructing the attack timeline.
- Investigating webshells and other attacker artifacts.
- Using Splunk to search logs and create detection queries.
- Testing the detection queries during further security testing.

## Lab Setup

The project used three virtual machines running Kali Linux:

- **VM1 – Target:** Hosted the web application and Apache logs.
- **VM2 – SIEM:** Used Splunk Enterprise for log analysis and detection.
- **VM3 – Attacker:** Used to test the application and simulate attacks.

## Tools Used

- Kali Linux
- Splunk Enterprise
- Apache
- SQL Injection Testing
- XSS Testing
- Command Injection Testing
- Log Analysis

## Project Report

The full report includes screenshots of the testing process, the fixes 
applied to the vulnerabilities, and the defensive investigation.

[View the Project Report](./masar%20final%20project.pdf)

## Team Members

- Faris Ishaq
- Wadee Alsallq
- Laith Naser
- Abdullah Altalafha

## Disclaimer

This project was conducted for educational purposes in a controlled 
lab environment. All testing was performed as part of the project.
