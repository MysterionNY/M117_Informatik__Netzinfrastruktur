# Checkpoints

## Tag 1
* Bit/Byte, k,M,G,T ki,Mi,Gi,Ti (Kurz darauf hingewiesen)
* Topologien (Bus, Baum, Mesh)
* Yellow-Coax-Cable vs. Twistedpair-LAN-Cable
* Materialwahl CU-Litze vs. CU-Draht vs. Glas
* Störungsabwehrmassnahmen Kabelschirm, TwistedPair
* Kabelaufbau S/FTP etc.
* Kabelkategorie CAT7 etc.
* Ethernetmedientyp 1000Base-T etc.
* Logisches Layout vs. Verkabelungsplan
* PCs verbinden Switch etc.

## Tag 2
Zugriffsverfahren CSMA/CD auf Netzwerkkabel?
* Hostname/Computername/Hostnameeingabe bei WIN?
(Tipp: sysdm.cpl)
* MAC-Adresse, statische Adresse, Unterscheide?
(Wichtiges Kommando für später: arp)
* IPv4-Adresse, dynamische Adresse, ipconfig-Kommando, ping-Kommand?Netzwerkeinstellungen in WIN (Tipp: ncpa.cpl)
* Private IP-Adressbereiche 10.x.x.x, 172.[16..31].x.x, 192.168.x.x, wann was?
* Zweck von Subnetzbildung?
* Funktion der Subnetzmaske?
Teilt IP-Adresse in Netz-ID und Host-ID
* Subnetzmaske in CIDR-Notation, Netzwerkadresse, Broadcastadresse,
Loopbackadresse?
Wir beschränken uns zurzeit auf folgende Subnetzvarianten: /8, /16 und /24
* Statische Netzwerkeinstellungen versus dynamischer mittels DHCP?
* APIPA-Adresse 169.254.x.x?
wenn kein DHCP verfügbar
* Router, verbindet Subnetze. Wie geht das?
WIN: Standardgateway, LIN:Default-Router

## Tag 3
* Funktionsweise Hub/Switch (Kollisionsdomäne)
* SAT-Tabelle (Switch)
* Internetzugang (war schon an Tag2 Thema)
* OSI-Schichtenmodell (7 Layers)
* TCP/IP-Stack
* Protokoll-Port-Nummern (System/Registered/Dynamic)
* arp-Protokoll (MAC-IP)
* Datenpaket verschicken (über Switch, über Router)

## Tag 4
* PRÜFUNG

## Tag 5
* 8-9h:   Praxisarbeit: Netzwerkfehlersuche mit FILIUS
        Gruppenweise Besprechung der LB2  (Pmax=37 Notenschnitt: 4.46)
 
* 9-11h:  Einführung Dateizugriffsrechte
        Lernziele: Benutzer/Gruppen
        Rechte auf Verzeichnisse/Dateien
        Implementierung in WIN
        Vererbung, Freigabe, Konzepte
        Hinweis auf die Wichtigkeit von vordefinierten WIN-Admin und System-Accounts
        Demo zu Benutzer/Gruppen erfassen, Berechtigungen erstellen in WIN
* 11-12h  Einführung "Virtuelle Maschinen"