# Logische Topologie

## Aufgabe
![Logische Topologie Aufgabe](/Images/Tag_7/Aufgabe_1_Logische_Topologie.png)

## Lösung
Die Netzadresse ist: `10.0.0.0/16`  
Jedes Subnetz erhält ein eigenes `/24`-Netz

| Subnetz | Netzwerkadresse | Broadcastadresse | IP-Adresse PC1     | IP-Adresse PC2     | Gateway          |
|---------|------------------|------------------|---------------------|---------------------|------------------|
| A       | 10.0.0.0/24      | 10.0.0.255       | 10.0.0.10           | 10.0.0.11           | 10.0.0.1         |
| B       | 10.0.1.0/24      | 10.0.1.255       | 10.0.1.10           | 10.0.1.11           | 10.0.1.1         |
| C       | 10.0.2.0/24      | 10.0.2.255       | 10.0.2.10           | 10.0.2.11           | 10.0.2.1         |
| D       | 10.0.3.0/24      | 10.0.3.255       | 10.0.3.10           | 10.0.3.11           | 10.0.3.1         |
| E       | 10.0.4.0/24      | 10.0.4.255       | 10.0.4.10           | -                   | 10.0.4.1         |
| F       | 10.0.5.0/24      | 10.0.5.255       | DHCP: 10.0.5.10     | DNS: 10.0.5.11      | 10.0.5.1         |
| G       | 10.0.6.0/24      | 10.0.6.255       | (Routerlink)        |                     |                  |
| H       | 10.0.7.0/24      | 10.0.7.255       | (Routerlink)        |                     |                  |
| I       | 10.0.8.0/24      | 10.0.8.255       | (Routerlink)        |                     |                  |
