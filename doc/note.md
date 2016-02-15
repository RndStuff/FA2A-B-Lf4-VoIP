## VOIP - Voice Over Internet Protocol
IP-Telefonie (kurz für Internet-Protokoll-Telefonie), auch Internet-Telefonie oder Voice over IP (kurz VoIP) genannt, ist das Telefonieren über Computernetzwerke, welche nach Internet-Standards aufgebaut sind.

IP-Telefonie ist eine Technologie, die es ermöglicht, den Telefondienst auf IP-Infrastruktur zu realisieren, so dass diese die herkömmliche Telefontechnologie samt ISDN und allen Komponenten ersetzen kann. Zielsetzung dabei ist eine Reduzierung der Kosten durch ein einheitlich aufgebautes und zu betreibendes Netz.



## Geschichte

### 1995
 Erste Vorstellung einer Telefonie über das Internet Protocol (IP) durch die israelischen Firma VocalTec mit ihrer Software "Internet Phone", damals von PC-zu-PC im Halduplex-Betrieb.
### 1996
 Erste Norm für Multimedia-Kommunikation über paketorientierte Netze ohne Quality of Service (H.323)
### 1997
 Entwicklung von H.323-Gateways  IP-Netz <-> öffentlichen Festnetz (PSTN)
### 1999
 Konkurrenz für H.323 Protokoll durch die Entwicklung des Session Initiation Protocols (SIP)
### 2003
 Testbetrieb von ENUM
### 2004
 SIP wird von allen deutschen VOIP-Diensten verwendet
### 2012 
 - rund 11,1 Millionen Menschen nutzten in Deutschland VOIP
 - Das entspricht 29,6 % aller Zugänge zur Sprachkommunikation
 - Wachstum von 45,1 % gegenüber Ende 2010

### 2018
 Alle Telekom-Kunden sollen nur noch übers Internet telefonieren

## Session Initiation Protocol (SIP)
Das Session Initiation Protocol ist ein Netzprotokoll zum Aufbau, zur Steuerung und zum Abbau einer Kommunikationssitzung zwischen zwei und mehr Teilnehmern. In der IP-Telefonie ist das SIP das standard Protokoll.

SIP-Adressen werden im URI-Format geschrieben, welches auch bei HTTP und EMAIL Anwendung findet.
- Unverschlüsselte SIP-Verbindung: sip:user@domain.
- Verschlüsselte SIP-Verbindung: sips:user@domain.
- Telefonnummer: tel:nummer, sip:nummer@domain.

## Merkmale
VoIP-Telefone melden sich beim Server (zum Beispiel SIP-Server) an, daher kennt der Server die aktuelle IP-Adresse der Telefone.

Mit Hilfe der IP-Adresse des Telefons, die dem Server bekannt gemacht wurde, kann er die Vermittlung übernehmen, und das angewählte IP-Telefon klingelt in Abhängigkeit von dieser IP-Adresse (also an einem beliebigen Ort in der Welt, wenn sich das IP-Telefon von dort aus beim Vermittlungsserver über das Internet registriert hat).

Die Kommunikation zwischen den IP-Telefonen kann unabhängig vom Server erfolgen.

Es gibt kommerzielle Dienste, die zugleich mit einem Account für den Vermittlungsserver ein lokales Telefon anbieten, welches zudem über das Festnetz erreichbar ist. Die IP-Telefonate sind in der Regel kostenlos.

## Wie funktioniert es?

### ATA = Analogue Terminal Adapter
Connects an Analogue Telephone to a VOIP network
Usually has an Ethernet jack, and an RJ-11 phone jack.

Sometimes referred to as VOIP Gateways, TA (Terminal Adapter), FXS Adapter, etc. Some ATAs are locked to a particular provider, and useless with any other. Virtually all ATAs use either the SIP or IAX industry standard protocol.

*Normales Telefon ---- ATA ---- Ethernet ---- Router ---- Internet ---- VOIP Service Provider*

### IP Phone
*Standalone Ethernet Hard Phones (voice only)*
An Ethernet hard phone is a self contained IP telephone that looks just like a conventional phone but instead of a conventional phone jack, it has an Ethernet port through which it communicates directly with a VoIP server, VoIP gateway or another VoIP phone. Since a broadband hard phone communicates directly with a VoIP server, VoIP gateway or another VoIP phone it does not require any personal computer nor any software running on a personal computer to make or receive VoIP phone calls. It can be used independently, all that is required is an internet connection. While PC based software solutions are cheaper, a hard phone is the best solution for IP telephony.

IP Telefon ----- Ethernet ----- Router ---- Internet ---- VOIP Service Provider

### Direkte Verbindung
IP Phone ----- Ethernet ----- Router ---- Internet ---- Router ---- Ethernet ---- IP Phone

## Vorteile:
- Weniger Kosten
- Leichtes erhöhen der Funktionalität
- Gespräche können ortsunabhängig angenommen werden

## Nachteile:
- Die Sprachqualität erreicht nicht immer den gewohnten Standard des ISDN-Anschlusses.
- Ausfallsicherheit. Bei einem Stormausfall wurden Telefone noch über die Telefonleitung mit Energie versorgt.
- Da Gespräche ortsunabhängig sind können Notrufe nicht sofort zugeortnet werden

## VoIP Software
- 3CX
- Skype
- Google Hangout
