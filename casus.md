# Casus – ROC SilentSent1nel

## Organisatie

ROC SilentSent1nel is een MBO-instelling gevestigd in Den Haag. De organisatie bestaat uit drie verschillende locaties waar studenten worden opgeleid in IT en technische vakgebieden.

De IT-infrastructuur wordt centraal beheerd vanaf de hoofdcampus (Site A).

---

## Locaties

De organisatie bestaat uit de volgende locaties:

- Site A – Hoofdcampus
  - Centrale IT-afdeling
  - Servers en netwerkdiensten

- Site B – Campus 2
  - Studentenomgeving
  - Leslokalen en werkplekken

- Site C – Campus 3
  - Technische labs
  - Praktijkomgevingen

---

## Netwerkeisen

Het netwerk moet voldoen aan de volgende eisen:

- Hoge beschikbaarheid van systemen
- Veilige communicatie tussen alle vestigingen
- Centrale netwerkdiensten
- Scheiding tussen studenten en beheernetwerken
- Schaalbaar ontwerp voor uitbreiding

---

## Netwerkontwerp

De drie locaties zijn verbonden via een WAN-structuur. Omdat verbindingen over het publieke internet onveilig zijn, wordt gebruik gemaakt van Site-to-Site VPN tunnels om het verkeer te beveiligen.

Voor routing tussen de locaties wordt het OSPF-protocol gebruikt, zodat routes automatisch worden uitgewisseld en het netwerk bestand is tegen storingen.

---

## Beveiliging

Beveiliging speelt een belangrijke rol in dit ontwerp:

- Versleutelde VPN-verbindingen tussen locaties
- Firewallregels op de routers
- Netwerksegmentatie tussen gebruikersgroepen
- Beperkte toegang tot interne systemen

---

## Centrale diensten

De hoofdcampus (Site A) bevat de centrale diensten:

- DHCP-Server (IP-adressen)
- DNS-Server (naamomzetting)
- Webserver (intranet)

---

## Scope

Dit project is een simulatie van een realistisch bedrijfsnetwerk. Cloudomgevingen en volledige enterprise directory-systemen vallen buiten de scope. Dit in verband met beperkte systeem middelen, denk dus aan CPU, RAM en opslag.

---