# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
<img width="1175" height="597" alt="Screenshot 2025-11-17 101927" src="https://github.com/user-attachments/assets/1b342d58-584d-4ef9-a995-4839899018c1" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="810" height="191" alt="Screenshot 2025-11-17 102032" src="https://github.com/user-attachments/assets/a03a2806-ff3c-4538-807d-d9b74cafe5b3" />

 dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="633" height="594" alt="Screenshot 2025-11-17 102306" src="https://github.com/user-attachments/assets/8b07955c-9b78-43f4-89e3-4500effb5570" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="491" height="163" alt="Screenshot 2025-11-17 102353" src="https://github.com/user-attachments/assets/fd9e5e90-5cba-4c08-94b8-8c8be78252ed" />


Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="792" height="405" alt="Screenshot 2025-11-17 102408" src="https://github.com/user-attachments/assets/09312894-f601-4ed4-ac05-3a70e5be8261" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
