# iptables – Linux Firewall Basics

## 🔹 View Rules
```bash
iptables -L -n -v
#Allow SSH
iptables -A INPUT -p tcp --dport 22 -j ACCEPT
#Block an IP
iptables -A INPUT -s 1.2.3.4 -j DROP
#Default Policies
sudo iptables -P INPUT DROP
sudo iptables -P FORWARD DROP
sudo iptables -P OUTPUT ACCEPT
#Allow local trafic
sudo iptables -A INPUT -i lo -j ACCEPT
#Delete Rule
sudo apt install iptables-persistent
sudo netfilter-persistent save
sudo netfilter-persistent reload
#Notes
#Chains: INPUT, OUTPUT, FORWARD

#Always keep SSH access open before applying DROP policies

#Use iptables-save and iptables-restore for scripting 
