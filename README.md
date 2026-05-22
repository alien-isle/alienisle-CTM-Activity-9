Activity # 10: adoVM CTM Terminal Simulator (Linux Networking Commands)



Repository: GitHub

https://github.com/xen0byt3/xen0byt3-CTM-Activity-10



Overview



The adoVM CTM Terminal Simulator is a Python-based terminal simulation designed to replicate basic Linux networking commands in a controlled environment.



This project is created for CTM Simulation students to practice:



&#x09;Networking fundamentals

&#x09;Command-line usage

&#x09;Cybersecurity concepts (SOC basics)



Objectives



&#x09;Simulate real-world Linux networking tools

&#x09;Interpret command outputs

&#x09;Understand network diagnostics

&#x09;Develop foundational cybersecurity skills



Features



&#x09;Simulated Linux terminal interface

&#x09;Predefined DNS and IP mappings

&#x09;Randomized outputs for realism

&#x09;Activity logging system

&#x09;File system simulation (ls, cat, wget)

&#x09;Admin vs non-admin command behavior



How to Download \& Run (from GitHub)



Repository:

https://github.com/xen0byt3/xen0byt3-CTM-Activity-10



Option 1: Download as ZIP (Easiest)



1\. Go to the repository link above

2\. Click the green “Code” button

3\. Select “Download ZIP”

4\. Extract the ZIP file on your computer

5\. Open the folder

6\. Double-click the .exe file to run



Option 2: Clone using Git (Optional)



1\. Open Command Prompt / Terminal

2\. Run:

&#x09;git clone https://github.com/xen0byt3/xen0byt3-CTM-Activity-10.git

3\. Open the downloaded folder

4\. Run the .exe file



Running the Program



&#x09;Simply double-click the .exe file

&#x09;A terminal window will appear

&#x09;Follow the setup instructions (hostname, IP, etc.)



Initial Setup  



When the program starts:

1\. Enter a Hostname

2\. Choose connection:

&#x09;Ethernet

&#x09;WLAN

3\. Enter a Class A IP Address (1–126 range)

&#x09;Example: 10.0.0.1

4\. Subnet mask is automatically:

&#x09;255.0.0.0


\[Commands Overview]

Basic Commands



&#x09;help

&#x09;ip a

&#x09;ip route

&#x09;hostname -I



Network Tools



&#x09;ping <target>

&#x09;traceroute <target>

&#x09;netstat -tulnp



DNS Tools



&#x09;nslookup <target>

&#x09;dig <target>



Scanning



&#x09;nmap <target>

&#x09;nmap -sV <target>

&#x09;nmap -A <target>



Monitoring



&#x09;arp-scan --localnet

&#x09;sudo arp-scan --localnet

&#x09;tcpdump -i <interface>



Web Tools



&#x09;curl <website>

&#x09;nc <ip> <port>

&#x09;whois <ip>



File System



&#x09;ls

&#x09;cat <filename>

&#x09;wget <filename>



System



&#x09;shutdown



\[Major Tasks]

Activity 1: Network Info



&#x09;ip a

&#x09;hostname -I



Activity 2: Connectivity Test



&#x09;ping 

&#x09;traceroute 



Activity 3: DNS Analysis



&#x09;nslookup

&#x09;dig



Activity 4: Port Scanning



&#x09;nmap

&#x09;nmap -sV

&#x09;nmap -A



Task 5: Traffic Monitoring



&#x09;tcpdump -i Ethernet



Task 6: Device Discovery



&#x09;arp-scan --localnet

&#x09;sudo arp-scan --localnet



Task 7: Logs \& Files



&#x09;ls

&#x09;cat

&#x09;wget

