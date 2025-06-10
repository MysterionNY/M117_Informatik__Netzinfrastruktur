# Port-Nummern

## Aufgabe
![Port-Nummern](/Images/Tag_3/Aufgabe_2_Port_Nummern.png)

## Lösung
### 1. Was bezweckt die logische Port-Nummer?
- Erlaubt Multiplexing mehrerer Anwendungen auf einer IP-Adresse.
- Trennt den Datenverkehr verschiedener Dienste (z. B. Web vs. E-Mail).
- Identifiziert Absender- und Empfänger-Sockets in Transportprotokollen (TCP/UDP).

### 2. Für die Portnummer sind wie viele Bit vorgesehen und wie lautet der Wertebereich?
- **Bit-Länge:** 16 Bit  
- **Wertebereich:** 0 … 65 535  

### 3. Wie lautet der Wertebereich der System-Ports (Well-known Ports)?
- **System-/Well-known Ports:** 0 … 1 023  

### 4. Wie lautet der Wertebereich der Registered Ports (User Ports)?
- **Registered Ports:** 1 024 … 49 151  

### 5. Wie lautet der Wertebereich der Dynamic (Private) Ports?
- **Dynamic/Private Ports:** 49 152 … 65 535  

### 6. Über welchen Portbereich kann das Betriebssystem frei verfügen?
- Dynamische/Private Ports (49 152–65 535) werden in der Regel vom Betriebssystem zufällig zugewiesen (Ephemeral Ports).

### 7. Protokollabkürzungen und ihre reservierten System-Portnummern
| Kürzel  | Voller Name                                    | Standard-Port |
|:--------|:-----------------------------------------------|:-------------:|
| HTTP    | Hypertext Transfer Protocol                    | 80            |
| HTTPS   | Hypertext Transfer Protocol Secure (TLS/SSL)   | 443           |
| FTP     | File Transfer Protocol                         | 21 (Kontroll-), 20 (Daten-) |
| SMTP    | Simple Mail Transfer Protocol                  | 25            |
| POP3    | Post Office Protocol version 3                 | 110           |
| POP3S   | POP3 over SSL/TLS                              | 995           |
| IMAP    | Internet Message Access Protocol               | 143           |
| IMAPS   | IMAP over SSL/TLS                              | 993           |
| Echo/Ping | Echo Protocol (ICMP–basiert)                 | 7             |
| DNS     | Domain Name System                             | 53            |
