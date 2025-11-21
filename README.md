# TCM_OSINT
JU5T L1NKS AND T00LS US3 TH3M A5 Y0U WANT


# 🕵️‍♂️ TCM OSINT Toolkit

<p align="center">
  <img src="https://raw.githubusercontent.com/tcm-sec/tcm-osint/main/img/banner.png" alt="TCM OSINT Banner" />
</p>

```
████████╗ ██████╗███╗   ██╗     ██████╗ ███████╗██╗███╗   ██╗████████╗
╚══██╔══╝██╔════╝████╗  ██║    ██╔═══██╗██╔════╝██║████╗  ██║╚══██╔══╝
   ██║   ██║     ██╔██╗ ██║    ██║   ██║█████╗  ██║██╔██╗ ██║   ██║   
   ██║   ██║     ██║╚██╗██║    ██║   ██║██╔══╝  ██║██║╚██╗██║   ██║   
   ██║   ╚██████╗██║ ╚████║    ╚██████╔╝██║     ██║██║ ╚████║   ██║   
   ╚═╝    ╚═════╝╚═╝  ╚═══╝     ╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═══╝   ╚═╝   
```

A powerful OSINT (Open Source Intelligence) resource list combined with essential reconnaissance tools and commands for cybersecurity professionals, ethical hackers, and researchers.

---

## 🔍 **OSINT Websites & Tools**

### **📧 Email OSINT**
- hunter.io
- phonebook.cz
- email-checker.net
- dehashed.com
- leakcheck.io
- snusbase.com
- scylla.sh
- weleakinfo.to/v2/

### **👤 Username / People Search**
- whatsmyname.app
- namecheckup.com
- namechk.com
- peekyou.com
- 411.com
- thatsthem.com
- spokeo.com

### **📞 Phone Lookup**
- calleridtest.com

### **🌐 Domain, DNS, IP & Infrastructure**
- viewdns.info
- builtwith.com
- centralops.net/co/
- spyonweb.com
- visualping.io
- urlscan.io
- dnsdumpster.com
- crt.sh
- shodan.io
- web.archive.org
- aihtidata.com

### **📡 Wireless / Metadata / Images**
- wigle.net
- exiftool.org
- imginn.com
- snapchat.com

### **📁 OSINT Tools**
- hunch.ly
- sowsearch.info

---

## 🛠️ **Linux Tools Installation**
```bash
sudo apt install sherlock
recon-ng
maltego
```

---

## 🚀 **Recon Commands**

### **WHOIS Lookup**
```bash
whois tcm-sec.com
```

### **Subdomain Enumeration**
```bash
subfinder -d tcm-sec.com
assetfinder tcm-sec.com
amass enum -d tcm-sec.com
```

### **Sorting + Probing Alive Domains**
```bash
cat tesla.txt | sort -u | httprobe -s -p https:443
```

### **Screenshot Recon with Gowitness**
```bash
gowitness file -f ./alive.txt -P ./pics --no-http
```

---

## 🎨 **Hacker-Style Banner**
```
┌──────────────────────────────────────────────┐
│   T C M   O S I N T   R E C O N   S U I T E   │
└──────────────────────────────────────────────┘
    ╲    ╱   ╲    ╱   ╲    ╱   ╲    ╱   ╲    ╱  
     ╲  ╱     ╲  ╱     ╲  ╱     ╲  ╱     ╲  ╱   
      ╳       ╳       ╳       ╳       ╳       
     ╱ ╲     ╱ ╲     ╱ ╲     ╱ ╲     ╱ ╲     
    ╱   ╲   ╱   ╲   ╱   ╲   ╱   ╲   ╱   ╲    
```

---

## ⭐ **Contribute**
Feel free to submit pull requests or suggest new OSINT tools!

## 📜 **License**
MIT

---

> **Made for OSINT researchers, cybersecurity students, and ethical hackers.**
