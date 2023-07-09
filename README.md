# PortScanner-using-NMAP

Introduction
This is a simple port scanning project implemented using the NMAP (Network Mapper) tool. The project aims to provide a straightforward and efficient way to scan for open ports on a target system or network.

Features
* Scans a specified target IP address or range of IP addresses for open ports.
* Supports scanning of individual ports or a range of ports.
* Provides the ability to specify the scanning technique or scan type (e.g., TCP SYN scan, TCP connect scan, UDP scan, etc.).
* Displays detailed information about open ports, including the service name, version, and additional details if available.
* Supports customization of various scanning parameters, such as timeout, maximum number of retries, and maximum number of simultaneous connections.
*Generates a report summarizing the scan results and saves it to a specified file.

Prerequisites
NMAP: Make sure NMAP is installed on your system. You can download it from the official NMAP website (https://nmap.org/).

Installation
* Clone the repository: git clone https://github.com/ByteWizard77/portscanner-nmap.git
* Change into the project directory: cd portscanner-nmap
* Install the required dependencies: pip install -r requirements.txt
  
Usage
* Open a terminal and navigate to the project directory.
* Run the script with the following command: python portscanner.py [options] target(s)
* Replace [options] with the desired scanning options (e.g., -p 1-100 for scanning ports 1 to 100).
* Replace target(s) with the target IP address or range of IP addresses to scan.
* Refer to the NMAP documentation for more information on available options and target specification.
* Wait for the scan to complete.
The scan results will be displayed in the terminal, including information about open ports and any available service details.
Additionally, a report file will be generated in the project directory, summarizing the scan results.
