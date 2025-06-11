# PENETRATION-TESTING-TOOLKIT

COMPANY:CODTECH IT SOLUTIONS

NAME:LAVANYA MUDDAPATI

INTERN ID:CT08DN1958

DOMAIN:CYBER SECURITY

DURATION:8 WEEKS

MENTOR:NEELA SANTOSH

Task-3: *PENETRATION TESTING TOOLKIT*
In this task, I was assigned to develop a modular penetration testing toolkit using Python, as part of my internship with CODTECH. The goal was to build a set of tools that can assist in basic ethical hacking activities, including port scanning and brute-force attacks. For this task, I focused on designing and implementing a Port Scanner module — one of the core components used in real-world security assessments.
Penetration testing, also known as ethical hacking, involves testing a computer system or network to identify vulnerabilities that malicious hackers could exploit. One of the first steps in any penetration test is to perform a port scan. A port scanner probes a target host to find which TCP ports are open and which services may be running on those ports. This helps an ethical hacker understand the attack surface of the system.
To implement this, I created a simple Python-based port scanner using the built-in socket module. The code uses socket.socket() to create a connection to the target machine and attempts to connect to a list of ports (provided by the user). If the connection is successful, it concludes that the port is open; otherwise, it reports the port as closed. I also added error handling for scenarios like incorrect IP addresses, unresolvable hostnames, or invalid port inputs.
The scanner was implemented in a modular format with two separate files:
*PORTSCANNER_MODULE.PY*: This file contains the actual port scanning logic in the form of a function called scan_ports(), which takes a target host and a list of ports as arguments.
MAIN.PY: This is the driver script that interacts with the user, takes input (target IP/domain and port numbers), and calls the scanning function from the module.
The code was thoroughly tested using common domains like scanme.nmap.org and localhost (127.0.0.1). The output clearly displayed which ports were open and which were closed, giving a visual insight into the system's network exposure.
The primary technologies used were:
Python 3,Socket Programming,VS Code for development
To ensure modularity, the logic was not written in one monolithic file but split into reusable components. This makes it easy to expand the toolkit later with other modules such as:
Brute-force login attempts
Directory brute-forcing,Network mapping Vulnerability scanning
*CONCLUSION*
This port scanner fulfills the initial phase of the penetration testing toolkit task. It introduces basic ethical hacking concepts and builds a strong foundation for more complex modules. The scanner was written with clarity, modularity, and user-friendliness in mind, making it suitable for both beginners and advanced users interested in cybersecurity. The knowledge gained from this task has enhanced my understanding of low-level networking and Python’s capability to build real-world cybersecurity tools.

*OUTPUT*

![Image](https://github.com/user-attachments/assets/4169999b-c28b-4d70-b4ee-cf12f4f3d7c3)

