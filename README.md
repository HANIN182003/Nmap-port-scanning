# Nmap-port-scanning
Nmap port scanning and service detection.
Network Discovery and Port Scanning with Nmap

Project Overview

A practical cybersecurity project focused on network discovery, host identification, port scanning, service detection, and basic operating system identification using Nmap and Zenmap.

The project was performed in a controlled/local network environment for educational and cybersecurity learning purposes.

Objectives

* Discover active devices on a local network.
* Identify open, filtered, and closed ports.
* Detect running network services.
* Identify service versions where available.
* Perform basic operating system detection.
* Visualize discovered hosts using Zenmap topology.

Tools Used

* Nmap
* Zenmap
* Windows

Network Range

The scan was performed against the local private network:

192.168.1.0/24

> *Note:* The scan was conducted only on a network where I had authorization to perform security testing.

Scanning Activities

1. Network Discovery

Nmap was used to identify active hosts within the local network range.

The scan identified multiple hosts that were online and available for further analysis.

2. Port Scanning

The discovered hosts were scanned to identify network ports and their current states.

The results included:

* Open ports
* Filtered ports
* Closed ports

3. Service Detection

Nmap was used to identify services associated with detected ports.

Examples observed during the scan included:

* SSH
* Telnet
* HTTP
* UPnP

4. Operating System Detection

Nmap’s OS detection capability was used to estimate the operating system of a discovered host based on network responses.

5. Network Topology

Zenmap’s topology view was used to visualize the relationships between discovered hosts on the network.

Results

The scan demonstrated how Nmap can be used for basic network reconnaissance and security assessment.

The results provided information about:

* Active hosts
* Exposed network ports
* Available services
* Service versions
* Operating system information
* Network topology

Security Observations

Open network services should be reviewed to determine whether they are necessary.

Examples of security considerations:

* Disable unnecessary services.
* Avoid insecure protocols such as Telnet when secure alternatives are available.
* Restrict access to administrative services such as SSH.
* Review exposed ports and firewall rules.
* Keep network services updated.

Screenshots

Screenshots from the scan are included in this repository to document the practical results.

Nmap Scan Output

Nmap Scan Output

Ports and Services

Ports and Services

Network Topology

Network Topology

Host Details

Host Details

Skills Demonstrated

* Network Reconnaissance
* Network Discovery
* Port Scanning
* Service Enumeration
* Basic OS Detection
* Nmap
* Zenmap
* Networking Fundamentals
* Security Assessment

Ethical Use

This project is intended for educational and authorized security testing only.

Nmap scans should only be performed against systems and networks that you own or have explicit permission to test.

Future Improvements

* Export scan results automatically to XML/HTML reports.
* Add a Python script to summarize Nmap results.
* Categorize discovered services by risk level.
* Add basic vulnerability assessment in a controlled lab environment.
