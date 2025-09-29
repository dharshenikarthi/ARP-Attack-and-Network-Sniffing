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
<img width="825" height="750" alt="image" src="https://github.com/user-attachments/assets/22e9775e-0d46-41ac-b758-9addefe81594" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="1117" height="438" alt="image" src="https://github.com/user-attachments/assets/fabcaa1a-0802-45bf-bdab-189e37312405" />


 dsniff:


<img width="1918" height="757" alt="image" src="https://github.com/user-attachments/assets/d90478a6-9725-47c0-b22f-24bbd88b9c07" />




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1018" height="880" alt="image" src="https://github.com/user-attachments/assets/fa619ad9-3953-4d62-8872-19ea71108eca" />
<img width="935" height="248" alt="image" src="https://github.com/user-attachments/assets/762df08c-6a41-4a8d-97b2-fca9e8703053" />




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1918" height="881" alt="image" src="https://github.com/user-attachments/assets/6cc98ba8-574f-4954-a9a6-c0501927b5f6" />

## Ettercap:
<img width="1918" height="926" alt="image" src="https://github.com/user-attachments/assets/e4ee0610-db55-432c-82b4-8958c83545ff" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
