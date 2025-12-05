# Wireshark-Network-Traffic-Analysis
Analysis of captured  network traffic using Wireshark. Includes packet inspection, filtering, protocol analysis, and identification of anomalies
Below are sample screenshots from my Wireshark packet analysis( Identifying information has been removed for privacy.)
Packet Inspection Example
![Packet Inspection](https://github.com/Shinichi-creator/Wireshark-Network-Traffic-Analysis/blob/main/Screenshot%202025-12-04%20230518.png?raw=true)
This screenshot just shows that I am inspecting packet 1-19. Each packet is showing me key details such as protocol, source IP, destination IP, length, and info fields.
TCP Handshake Example
![TCP Handshake](https://github.com/Shinichi-creator/Wireshark-Network-Traffic-Analysis/blob/main/Screenshot%202025-12-04%20230935.png?raw=true)
This screenshot shows a complete TCP three way handshake(SYN, SYN-ACK, ACK), which establishes a reliable coneection betwwen a client and server.
DNS Query Example
![DNS Query](https://github.com/Shinichi-creator/Wireshark-Network-Traffic-Analysis/blob/main/Screenshot%202025-12-04%20231012.png?raw=true)
The screenshot shows DNS traffic where my device(source IP) is sending DNS queries to the DNS server (destination IP). Each packet includes the DNS server IP address as the destination for the request, and the server returns a response back to my device.
