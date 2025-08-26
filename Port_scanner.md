This port scanner is just the same as a generic Nmap scanner. Although I have made it so I have different commands such as -t for target, -p for ports, etc etc. this uses multithread, basic options for type of port scanning, anonymity features, and port scanner with stealth techniques to make it harder to detect. Creating this port scanner has stealth and evasion, of course this isn't 100% foolproof but still works well, using random timing that Nmap usually does. It has Custom TCP Stack Fingerprinting, bypassing OS detection since it doesn’t use Nmap’s packet patterns. It randomizes source ports than most tools can effectively do. *(In terms of my tool for myself)* And lastly it does mixed scan patterns, which doesn’t follow sequential or common patterns that IDS/IPS expect. Does this work 100%, maybe not for lab grade pentests but I’ll definitely work on it as I gain more skills and knowledge for port scanning tools and scripts. But this works well for myself and my own productivity as of right now. More details and definitely more features will be added later. Runs on Linux with python as well.

‎ 

Basic port scanner menu.

<img width="1722" height="406" alt="1" src="https://github.com/user-attachments/assets/f9eda01f-3057-4129-ae5d-b0713c6c8875" />

‎ 

Standered port scan without anything else being used, might be slow but I have another tool that is faster for it, but less stealth, I'd only use it if I know who my target is.

<img width="749" height="267" alt="2" src="https://github.com/user-attachments/assets/480359a2-a868-4a49-8794-c4b970ba84b8" />

‎ 

Port scan with level 4 stealth, slower, and logs every port, but still works.

<img width="503" height="814" alt="4" src="https://github.com/user-attachments/assets/ab1e2d27-815e-40d8-95dc-e8d1c4f43d6f" />

‎ 

Results when an open port with level 4 stealth is found, sticks out and still easy to find and read.

<img width="274" height="342" alt="3" src="https://github.com/user-attachments/assets/eaacf0ca-3fb5-49fe-bae4-4fc76044bd8d" />

‎ 

This prioritizes speed and multithreads allowing for a super fast port scan, while it's fast, making a dedicated port scanner for speed over stealth is something I would make for personal use potentially allowing faster port scans than what was shown, .55 seconds.

<img width="745" height="315" alt="5" src="https://github.com/user-attachments/assets/13880aec-051b-4cd5-abc5-db2b7172da8b" />

‎ 

After doing a second time with more variables, you can narrow it down, and make it stealthy and quick. I still have one brain cell.

<img width="749" height="351" alt="Screenshot 2025-08-26 003646" src="https://github.com/user-attachments/assets/63af587e-3157-4bea-bc57-f1905eda5006" />

‎ 

This is an updated version, 1.9.1. Added plentiful features if needed during more advanced port scans.

<img width="1865" height="668" alt="Screenshot 2025-08-26 140138" src="https://github.com/user-attachments/assets/077c9ec1-7b49-41c8-87a4-6a24b6f1e6b0" />
