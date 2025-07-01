# Wireshark

## Aufgabe
11 Aufgaben mit Wireshark Lösung auf Basis der erhaltenen PDF


### **1. Displayfilter für das Anpingen eines Rechners**
`icmp`

 
### 2. Kommando, um den Lokalhost anzupingen
```bash
ping 127.0.0.1
```

 
### 3. Ping an den Lokalhost – Was zeigt Wireshark?
Wireshark zeigt ICMP-Pakete (Echo Request und Echo Reply), allerdings nur, wenn der Netzwerkverkehr über eine Netzwerkschnittstelle läuft. Beim `127.0.0.1`-Ping (Loopback) wird meist **kein Paket** in Wireshark sichtbar, da es die Netzwerkschnittstelle nicht verlässt. Nur mit spezieller Loopback-Erfassung sichtbar.

 
### 4. Wie findet man die Router-IP des lokalen Netzwerks?
Über die Kommandozeile:
```bash
ipconfig (Windows)
ip route | grep default (Linux/Mac)
```
Dort steht die **Default Gateway IP-Adresse**, also die Router-IP.

 
### 5. Router anpingen – Wireshark-Analyse
Es werden ICMP Echo Requests an den Router gesendet und Echo Replies empfangen. Wireshark zeigt:
- ICMP Pakete
- Ziel-IP ist die des Routers
- MAC-Adresse des Routers als Empfänger (Layer 2)
 

### 6. Gibt es bei Ping einen OSI-Layer 4 (Transport-Layer)?
**Nein.** ICMP gehört direkt zum **Netzwerk-Layer (Layer 3)** und nutzt keinen Transport-Layer wie TCP oder UDP.
 
### 7. Zeichnen sie nun die DNS-Abfrage mit Wireshark auf.

### 8. inden sie nun mit Wireshark heraus, welches Protokoll DNS verwendet. TCP oder UDP?