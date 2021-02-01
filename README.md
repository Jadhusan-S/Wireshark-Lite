# Wireshark-Lite
Sniffer Using Python! 

### [What is the Use?](https://en.wikipedia.org/wiki/Packet_analyzer)
    Packet sniffer that can intercept and log traffic that passes over a computer network or part of a network.
    
### USAGE 
- [x] ICMP
- [x] ARP
- [x] IPv4
- [x] TCP
- [x] UDP
- [ ] OTHER
- [x] I have tested this program on Windows 10 Enterprise using WSL ver 2.

![WinVer](./Screenshots/1.JPG) ![WinVer](./Screenshots/pw.JPG)
-----------------------------------
###       W I N D O W S
-----------------------------------
Excute this program using WSL
- open WSL Terminal
- navigate to  file path
- type the following command
>python3 sniffer.py www.github.com [DomainName] <br/>
>python3 sniffer.py 8.8.8.8 [IpAddr] <br/>
-----------------------------------
###         L I N U X
-----------------------------------
- open terminal
- navigate to file path
- type the following command
>sudo python3 sniffer.py www.github.com [DomainName] <br/>
>sudo python3 sniffer.py 8.8.8.8 [IpAddr] <br/>

### REQUIRMENT
- Run using SUDO privilege
- pip3 install -r requirements.txt
- Run using Administration privilege
- pip install -r requirements.txt

### The OUTPUT of the PROGRAM

 - ICMP
 
![Screenshot](./Screenshots/Output.JPG)

 - UDP
 
![Screenshot](./Screenshots/udp.jpg)

 - ARP
 
![Screenshot](./Screenshots/arp.jpg)

### Demonstration 

![](/Screenshots/output.gif)
