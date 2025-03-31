## Conception des documents
<p align="right"><a href="README.md">(Retourner au sommaire)</a></p>

**1 - Plan d'adressage IPv4 (LLA) :**

![image](https://github.com/user-attachments/assets/906bad05-5882-4f4b-bf39-659d88790f5d)

**2 - Listing machines :**

![image](https://github.com/user-attachments/assets/d306d904-e6f0-4f4a-9cd8-8fdc0e14e584)

**3 - Schéma synoptique :**

![image](https://github.com/user-attachments/assets/a743eee6-3ace-41d3-868a-b112f258a1b6)

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

5 -Protocole, Port, Description :

![image](https://github.com/user-attachments/assets/250733f6-9ee6-432c-8bf1-746963d610fd)

<a href="README.md">(Retourner au sommaire)</a>
