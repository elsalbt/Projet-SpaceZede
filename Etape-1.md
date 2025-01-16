## Conception des documents
<p align="right"><a href="README.md">(Retourner au sommaire)</a></p>

**1 - Plan d'adressage IPv4 et IPv6 (LLA et ULA) :**




**2 - Listing machines :**
![image](https://github.com/user-attachments/assets/da6f1b86-0e33-4537-9cfe-9c6a5cf58b9e)



**3 - Schéma synoptique :**


![image](https://github.com/user-attachments/assets/3158902c-4aa9-4ebd-9723-d5629ba4d6a1)


**4 - Matrice des flux :**

| Source / Service          | [ADDS (Kerberos/LDAP)] | DNS | DHCP | Serveur de fichiers (SMB) | Serveur téléphonique (SIP) | Serveur GLPI | Serveur Web |
|---------------------------|:----------------------:|:---:|:----:|:-------------------------:|:-------------------------:|:------------:|:-----------:|
| Client                    |           X            |  X  |   x  |             x             |            x              |      x       |      x      |
| Serveur ADDS (DNS/LDAP)   |                        |  X  |   x  |             x             |            x              |      x       |      x      |
| Serveur DNS               |                        |  X  |   x  |             x             |            x              |      x       |      x      |
| Serveur DHCP              |                        |  x  |   x  |             x             |            x              |      x       |      x      |
| Serveur de fichiers       |                        |  x  |   x  |             x             |            x              |      x       |      x      |
| Serveur téléphonique      |                        |  x  |   x  |             x             |            x              |      x       |      x      |
| Serveur GLPI              |                        |  x  |      x|             x             |            x              |      x       |      x      |
| Serveur Web               |           x            |  x  |   x  |             x             |            x              |      x       |      X      |


<a href="README.md">(Retourner au sommaire)</a>
