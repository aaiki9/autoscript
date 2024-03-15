# UPDATE & UPGRADE REPO OS DEBIAN
<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade && sleep 0.5 && reboot</code></pre>
  
  
# UPDATE & UPGRADE REPO OS UBUNTU
<pre><code>apt update -y && apt upgrade -y && update-grub && sleep 0.5 && reboot</code></pre>
 

### INSTALL SCRIPT 
<pre><code>apt install -y wget screen curl && wget -q https://raw.githubusercontent.com/aaiki9/autoscript/main/ubu20-deb10-stable.sh && chmod +x ubu20-deb10-stable.sh && screen -S setup ./ubu20-deb10-stable.sh</code></pre>

### TESTED ON OS
- UBUNTU 18 / 20
- DEBIAN 9  / 10
### SUPPORT PORT
```
- SSL/TLS : 443 / 8443
- SSHWS   : 80 / 8880 / 8080 / 2082 / 2095 / 2096 / 2022 / 2092
```
