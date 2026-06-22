# Dit is een logboek waarin ik alles probeer bij te houden, van documentatie, systeemconfiguraties helemaal tot aan versiebeheer

17-6-2026:

- Github repo aangemaakt
- Initial commit met daarin: "Systemen ROC SilentSent1nel.docx" en "casus ROC SilentSent1nel.docx"
- "Systemen ROC SilentSent1nel.docx" en "casus ROC SilentSent1nel.docx" verwijderd en vervangen met:
-- README.md en casus.md
- ipv4 plan opgesteld en gepushed naar de repo

#### Site A:
- Router Site A image geïnstalleerd
- Netwerktekening V1 gemaakt en gepushed naar de repo

18-6-2026:

#### Site B:
- Router Site B image geïnstalleerd
- SSH service geactiveerd op router Site-A
- Banners geconfigureerd op router Site-A
- Interfaces op router Site-A geconfigureerd
- SSH service geactiveerd op router Site-B
- Banners geconfigureerd op router Site-B
- Interfaces op router Site-B geconfigureerd

#### Site C:
- Router Site C image geïnstalleerd
- SSH service geactiveerd op router Site-C
- Banners geconfigureerd op router Site-C
- Interfaces op router Site-C geconfigureerd

#### Untrusted internet router:
- Untrusted router image geïnstalleerd
- SSH service geactiveerd op untrusted router
- Banners geconfigureerd op untrusted router
- Interfaces op untrusted router geconfigureerd
- Github directory "documentatie" aangemaakt
casus.md verwijderd en opnieuw aangemaakt in:
https://github.com/Mirkan-23/Project-1-Site-to-Site-VPN/tree/main/documentatie/casus.md

- Github directory "Netwerk" aangemaakt
- Netwerktekening V1.png verwijderd van de Github hoofd directory
- Netwerktekening V1.png gepushed naar:
https://github.com/Mirkan-23/Project-1-Site-to-Site-VPN/tree/main/Netwerk/

- ipv4 plan verplaatst naar Github directory "Netwerk"
- OSPF routingprotocol op routers Site-A, Site-B en Site-C geconfigureerd
- NAT Overload (PAT) op Site-A geconfigureerd d.m.v. 2x source rule's

19-6-2026 en 20-6-2026:

#### Site-A:
- Rule 10 verwijderd
- VPN Configuratie toegevoegd op Site-A
- VPN-Config_Site-A.conf toegevoegd aan repo directory: https://github.com/Mirkan-23/Project-1-Site-to-Site-VPN/tree/main/Config/Routers
- OSPF werking aangepast op Site-A
- Rule 10 (Zoals op Site-A stond) toegevoegd aan Site-B router
- Rule 10 (Zoals op Site-A stond) toegevoegd aan Site-C router

21-6-2026:

- Rule 10 verwijderd van Site-B en Site-C router
- VPN Configuratie toegevoegd op Site-B
- VPN Configuratie toegevoegd op Site-B

STATUS VPN:
Site-A: ipsec sa is UP richting Site-B en Site-C
Site-B: ipsec sa is UP richting Site-A en Site-C
Site-C: ipsec sa is UP richting Site-A en Site-B

- VPN-Config_Site-A.conf, VPN-Config_Site-B.conf en VPN-Config_Site-C.conf verplaatst naar:
https://github.com/Mirkan-23/Project-1-Site-to-Site-VPN/tree/main/Config/Routers/VPN%20Configs

22-6-2026:

- Debian 13 minimal instance geïnstalleerd om DHCP services aan te bieden d.m.v. KEA.
-- ROC-DHCP
- DHCP Server geconfigureerd
- DHCP Relay geconfigureerd op Site-A, Site-B en Site-C
- 2 VM's ter netwerk test doeleinden gedeployed in de omgeving:
-- PuppyLinux-Test-VM-1
-- W10-Test-VM-2

- Debian 13 minimal instance geïnstalleerd om DNS services aan te bieden d.m.v. Unbound.
-- ROC-DNS

- Poging tot DHCP-Relay issue's debuggen (Deels DHCP Relay kunnen fixen)