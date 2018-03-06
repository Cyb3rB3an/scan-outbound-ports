# scan-outbound-ports
How to scan for open outbound ports

Everyone concentrates on scanning a network perimeter from the ouside in. 
It is also important to scan from the inside network out to see what ports are open for users. 
This can help reduce the impact the user based incident

http://portquiz.net/ can be used for this type of scan.

The below NMAP scan can be used to check for open outbound ports.

nmap -p1-65000 portquiz.net

For bigger networks running this command on multiple machines will give a better understanding of open ports.
