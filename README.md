# Network-Packet-Analysis
This report outlines the analysis of network traffic captured during a potential security incident involving a company's web server. The incident was investigated using the tool Wireshark to uncover key information about the attack.

Key Findings:
Compromised Credentials: The victim's username ("SMITH") and password ("SMITH!123") were identified through HTTP POST request analysis.
Server Details: The server was identified as running on nginx/1.19.0.
Attack Type: The attacker performed a Denial of Service (DoS) attack using SYN Flood, overwhelming the server with numerous SYN packets.
Attacker’s IP: The source IP of the attacker was identified as 77.235.113.10, associated with previous malicious activity.
Attacker’s Country: The attacker's IP was traced to Moldova using the MaxMind GeoLite2 database and VirusTotal services.
Disrupted Service: The attack targeted the FTP service (port 21), denying users access.

Recommendations:
Implement stronger authentication mechanisms (e.g., multi-factor authentication) to secure user credentials.
Continuous network monitoring for abnormal activity.
Deploy and configure firewalls and IDS/IPS to detect and mitigate DoS attacks.
Employee training on cybersecurity practices to reduce credential theft risks.
Regular software updates to minimize vulnerabilities.
By applying these recommendations, the organization can bolster its cybersecurity defenses against future threats.

Contributors: Ivan Kasvan Opio, Austine Baraka, Barnice Wakiro Njoroge, Murungi Micheal Charles, Emmanuel Kofi Ansah-Anobah, Kitso Bantom, Emelda Adhiambo, Leon Marienga, and Buyondo Vale.
