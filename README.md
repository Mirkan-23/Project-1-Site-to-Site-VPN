# ROC SilentSent1nel – Netwerk Infrastructuur lab
- Versie: V2

## Over het project

ROC SilentSent1nel is een gesimuleerde MBO-instelling gevestigd in Den Haag met drie verschillende locaties. Dit project is opgezet als een realistische netwerk-infrastructuur om netwerkbeheer, routing en security in een multi-site omgeving te oefenen.

De volledige omgeving wordt gevirtualiseerd met VMware Workstation en richt zich op praktische netwerkconcepten zoals VPN, dynamische routing en netwerksegmentatie.

---

## Netwerkopbouw

De omgeving bestaat uit de volgende locaties:

- Site A – Hoofdcampus (centrale IT, beheer en studentenomgeving)
- Site B – Campus 2 (studentenomgeving)
- Site C – Campus 3 (technische labs en studentenomgeving)
- ISP – Onbetrouwbaar internet (simulatie)

De locaties zijn met elkaar verbonden via een WAN-structuur met beveiligde VPN-verbindingen.

---

## Gebruikte technologieën

- 3x VyOS (routing, VPN en firewallfunctionaliteit)
- 1x VyOS (Untrusted internet)
- Debian Minimal DHCP-Server 
- Debian Minimal DNS-Server 
- Debian Minimal Webserver
- OSPF (dynamisch routingprotocol)
- Site-to-Site VPN
- VMware Workstation

---

- Simuleren van een realistisch multi-site netwerk
- Veilige communicatie tussen locaties opzetten
- Dynamische routing toepassen met OSPF
- Centrale netwerkdiensten op Site A
- Netwerksegmentatie tussen gebruikersgroepen
- Verkeer analyseren met Wireshark

---

## Belangrijkste functies

- Beveiligde VPN-verbindingen tussen sites
- Dynamische routing met OSPF
- Centrale DHCP en DNS server
- Interne webserver (intranet simulatie)
- Scheiding tussen student- en beheernetwerken
- Firewallfunctionaliteit op routers

---

## Structuur van het project

---

## Status

In ontwikkeling: ontwerp en opbouwfase

---

## Auteur

Mirkan Yalçin/SilentSent1nel