<h1>Packet_sniffer</h1>


<h2>Description</h2>
- HTTP Sniffer Script <br>
<br>This script captures and analyzes HTTP traffic on a specified network interface to detect potential login information. It extracts URLs from HTTP requests and searches for keywords related to login credentials within the packet payloads.
<br>

<br>Features: <br>
- Packet Sniffing: Listens for packets on a specified network interface without storing them permanently.<br>
- URL Extraction: Extracts the full URL from HTTP requests.<br>
- Login Information Detection: Searches for keywords related to login credentials in the packet payloads.<br>
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 


<h2>Environments Used </h2>

- <b>Linux</b> 

<h2>Usage: </h2>
 Run the script with the required options:
<br>sudo python http_sniffer.py

<br> The script is configured to sniff traffic on the eth0 interface. Modify the interface name as needed.<br>
<br><b>Requirements:</b>
<br>Python 3.x
<br>Scapy library (pip install scapy)
<br>Root or sudo privileges for packet sniffing

<br>
<b>This project is just for the study purpose...</b>
