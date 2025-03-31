## Configuration du réseau
<p align="right"><a href="README.md">(Retourner au sommaire)</a></p>

**Description de l'étape :** 

**1 - Configuration du routeur pfSense :**
* Une fois pfsense installer.

* Changer l'adresse IP de l'interface LAN donc choisissez l'option "2" et valider puis encore 2 pour choisir le LAN et valider.
![image](https://github.com/user-attachments/assets/ff241f84-9186-42c2-97f1-fe0424d71e1a)

* Entrer la nouvelle adresse "Gateway" puis le CIDR

* Ensuite taper 2 fois sur "entrer" puis 2 fois sur "n"

  ![image](https://github.com/user-attachments/assets/baee7f5c-5068-4b10-b514-e1dde6e5e273)

*Ensuite, vous aurez l'adresse de connection pour l'interface de pfsense.

**2 - Configuration des VLANs :**

* Dans pfsense, il faut aller dans "interfaces" puis Assignement.

![image](https://github.com/user-attachments/assets/30222836-914b-4dc6-8268-10393eeb1a51)

* Aller dans VLANs puis sur +Add

![image](https://github.com/user-attachments/assets/6f83167f-a0bd-40ee-87d8-d85adb1ded0a)

* Ensuite, configurer votre "VLAN" comme ci dessous. Attention de ne pas choisir les cartes "WAN et "LAN". Remplir les champs puis "SAVE"

![image](https://github.com/user-attachments/assets/db6a6475-44de-4ca6-b80e-195e19c86606)

* Retourner dans interface puis Assignments. Cliquer sur la carte pour choisir votre vlan puis sur Add

![image](https://github.com/user-attachments/assets/b74cb507-db01-4eab-8be5-d2631df330e7)

* Ensuite cliquer sur le vlan pour le configurer.

![image](https://github.com/user-attachments/assets/7394ff7a-20ed-46a3-940b-6521b498cc9c)

* Une fois dans le vlan, cliquer sur "Enable" puis suivre les instructions.

![image](https://github.com/user-attachments/assets/eb094061-7ef7-4a9b-949e-316a8bd8f589)

* Configurer l'adresse IPV4 "Gateway" et le "CIDR" puis "SAVE"

  ![image](https://github.com/user-attachments/assets/b1210b2b-9e4d-40c1-ae56-6b605e3d9697)

**3 - Filtrage réseau :**
* Voici l'une des régles de filtrage réseau

![image](https://github.com/user-attachments/assets/0140b58c-8b8c-4449-be95-b0601ff0732c)

![image](https://github.com/user-attachments/assets/4bdb6527-ed8b-402c-bbb7-1750642b20fd)

![image](https://github.com/user-attachments/assets/80dc13d6-07c3-49ba-a568-f48a790a485a)

![image](https://github.com/user-attachments/assets/ca90fa28-b2a4-45d0-8145-c386a97e0be8)

![image](https://github.com/user-attachments/assets/6076f024-7ffc-4bd4-af57-4270ad0cb226)

<a href="README.md">(Retourner au sommaire)</a>
