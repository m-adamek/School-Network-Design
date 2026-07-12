# School Network Infrastructure Design

Projekt sieci komputerowej dla szkoły średniej przygotowany w Cisco Packet Tracer.

## Opis projektu

Celem projektu było zaprojektowanie bezpiecznej, skalowalnej i łatwej w zarządzaniu infrastruktury sieciowej dla szkoły liczącej ponad 800 uczniów i 70 pracowników.

Projekt obejmuje:

- architekturę sieci opartą na modelu Core-Distribution-Access,
- segmentację sieci z wykorzystaniem VLAN,
- wdrożenie sieci Wi-Fi dla różnych grup użytkowników,
- telefonię VoIP,
- serwerownię z usługami DNS, Active Directory i File Server,
- analizę zagrożeń oraz dobór zabezpieczeń.

## Technologie

- Cisco Packet Tracer
- VLAN
- Inter-VLAN Routing
- Trunking
- Wi-Fi
- VoIP
- ACL
- Network Security
- Network Design

## Architektura

![Network Diagram](images/network-overview.png)

Sieć została podzielona na logiczne segmenty:

| VLAN | Przeznaczenie |
|--------|--------|
| VLAN 10 | Administracja |
| VLAN 20 | Nauczyciele |
| VLAN 30 | Uczniowie |
| VLAN 40 | Goście Wi-Fi |
| VLAN 50 | VoIP |
| VLAN 99 | Serwery |

## Kluczowe elementy projektu

### Serwerownia

- Core Switch L3
- Router dostępowy
- Active Directory Server
- File Server
- DNS

### Bezpieczeństwo

- segmentacja ruchu przy użyciu VLAN
- oddzielna sieć dla gości
- ACL
- MFA
- szyfrowanie danych
- backup offline
- EDR/XDR
- analiza ryzyka zgodna z BSI

### Infrastruktura bezprzewodowa

- wielopiętrowe pokrycie Wi-Fi
- osobne sieci dla uczniów, nauczycieli i gości
- integracja z VLAN

## Dokumentacja

Pełny raport projektu znajduje się w katalogu `docs`.

## Autorzy

Miłosz Adamek  
Projekt wykonany w ramach przedmiotu Bezpieczeństwo Systemów Informatycznych.
