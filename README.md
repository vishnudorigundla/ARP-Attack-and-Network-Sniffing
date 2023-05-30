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
![image](https://github.com/vishnudorigundla/ARP-Attack-and-Network-Sniffing/assets/94175324/7b9169b2-a424-4b4a-be8a-fab61af9f36b)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/vishnudorigundla/ARP-Attack-and-Network-Sniffing/assets/94175324/9357ec27-fb5b-411c-9fc8-c4ed8f19f4fa)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![image](https://github.com/vishnudorigundla/ARP-Attack-and-Network-Sniffing/assets/94175324/3a6811e4-5aac-46d4-9ddd-5715b8cec8c4)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/vishnudorigundla/ARP-Attack-and-Network-Sniffing/assets/94175324/f06d8449-fbfe-4b71-89c8-159d641021dc)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/vishnudorigundla/ARP-Attack-and-Network-Sniffing/assets/94175324/858718ed-dad6-4242-ba08-aec130e8cd6b)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
