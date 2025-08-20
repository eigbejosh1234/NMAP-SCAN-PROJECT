# NMAP-SCAN-PROJECT
This project is aimed at identifying devices in a network,uncovering open ports, and checking for vulnerabilities.

download Nmap from the official website  and run the installer.
https://nmap.org/download.html

**##find your network rang##**
To find network range/IP Address on macos terminal, use command promt. ipconfig getifaddr en0


<img width="236" height="26" alt="Screen Shot 2025-08-14 at 12 32 43 PM" src="https://github.com/user-attachments/assets/95520555-aaf4-494c-a908-9f84d2ead3c9" />


**##Discover devices on the network##**
To discover the devices on the network, use command prompt.  nmap -sn 192.168.72.0/24

<img width="258" height="48" alt="Screen Shot 2025-08-14 at 1 07 07 PM" src="https://github.com/user-attachments/assets/b264226a-5cd9-4257-8a48-e62e4827fe42" />


**##scan for open port##**
To scan for open port, pick one of the result you got through discovery of network devices using command prompt. nmap -Pn -sV 192.168.72.103

<img width="280" height="48" alt="Screen Shot 2025-08-14 at 5 22 16 PM" src="https://github.com/user-attachments/assets/ba5354d2-f979-4589-bbb0-7cadc3d0494d" />


**##Identify service##**
To identify service, (DNS) Domain,Name,Service. also use the command prompt with your selected ip -Pn -sV 192.168.72.103. The service runing on the device is (D.N.S) SERVICE


<img width="280" height="48" alt="Screen Shot 2025-08-14 at 5 22 16 PM" src="https://github.com/user-attachments/assets/b79543a8-f2cd-4edd-93fe-2d8497ace05e" />



**##Record your findings##**
create a table of ip addresses, device types, open ports, and services found

https://docs.google.com/spreadsheets/d/1COk13AGqnVdkFjCBow0nbUAPNBqYKbIbze6Ym7bLjcA/edit?usp=sharing


