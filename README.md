
# ARP-Attack-and-Network-Sniffing
## Name: Sharan kumar G
## Reg.no: 212224100055
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
<img width="984" height="637" alt="Screenshot 2025-10-04 081801" src="https://github.com/user-attachments/assets/7b819a73-4a33-404a-ad8d-bbfde98b5a80" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


 dsniff:
<img width="1920" height="1080" alt="KALI 2  Running  - Oracle VirtualBox 04-10-2025 08_22_44" src="https://github.com/user-attachments/assets/b4f24c7a-1233-4402-80b5-19fc7085ea25" />






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1920" height="1080" alt="KALI  Running  - Oracle VirtualBox 20-09-2025 09_10_20" src="https://github.com/user-attachments/assets/6bf1668c-8225-4eea-a3e9-0e7442d29f70" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
