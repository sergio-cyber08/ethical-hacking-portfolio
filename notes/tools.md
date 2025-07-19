# 🛠️ Appunti Strumenti

---

## 🔍 Nmap – Network Scanner

nmap indirizzo         # scansione base  
nmap -sV indirizzo     # versione dei servizi  
nmap -p- indirizzo     # tutte le porte  
nmap -A indirizzo      # scan avanzato (OS, versioni, script)  

---

## 🧪 Wireshark – Packet Sniffer

- Interfaccia grafica per analizzare pacchetti di rete  
- Filtri utili:  
  - ip.addr == 192.168.1.1  
  - tcp.port == 80  
  - http  

---

## 🕷️ Burp Suite – Web Testing Proxy

- Strumento per intercettare, modificare e analizzare traffico HTTP  
- Modalità:  
  - Proxy → intercetta richieste  
  - Repeater → reinvia richieste  
  - Intruder → attacchi automatizzati  

---

## 🐚 Netcat – Swiss Army Knife

nc -lvp 4444              # ascolta su una porta  
nc indirizzo 4444         # connessione a una porta  

---

## 🧠 Note personali

- Nmap è la prima arma da usare per esplorare una macchina  
- Wireshark serve per *capire cosa succede nella rete*  
- Burp Suite è fondamentale per testare siti web
