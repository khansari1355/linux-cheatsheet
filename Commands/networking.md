# Networking Commands in Linux

## 🔹 IP Address & Interfaces

```bash
ip a
ifconfig
hostname -I
# Check Connectivity
ping google.com
traceroute google.com
curl http://example.com
curl ifconfig.me
# Download Files
wget http://example.com/file.zip

# Check Listening Ports
ss -tuln
netstat -tulnp
#DNS Lookup
nslookup google.com
dig google.com
#💡 Notes
#Use ip a instead of ifconfig in modern systems

#ss is faster and more reliable than netstat

#dig gives more details than nslookup

