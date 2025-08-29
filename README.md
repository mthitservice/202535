## 202535
# Weindows Server 2025 Administrator Grundlagen

> Trainer Michael Lindner
>
> # Netzwerkgrundlagen für Windows Server Administratoren

## OSI-Schichtenmodell

Das OSI-Modell (Open Systems Interconnection) besteht aus sieben Schichten, die die Kommunikation zwischen Computersystemen strukturieren:

1. **Bitübertragungsschicht (Layer 1)** – Übertragung von Bits über physikalische Medien (z. B. Kabel, Modem, Hub)
2. **Sicherungsschicht (Layer 2)** – Fehlererkennung und MAC-Adressierung (z. B. Switch, Bridge)
3. **Vermittlungsschicht (Layer 3)** – Routing und IP-Adressierung
4. **Transportschicht (Layer 4)** – TCP/UDP, Datenflusskontrolle
5. **Sitzungsschicht (Layer 5)** – Sitzungsverwaltung
6. **Darstellungsschicht (Layer 6)** – Datenformatierung und Verschlüsselung
7. **Anwendungsschicht (Layer 7)** – Schnittstelle zu Anwendungen (z. B. HTTP, FTP, SMTP)

Quelle: [Netzwerktechnik](https://mthcloud-my.sharepoint.com/personal/michael_lindner_mth-it-service_com/_layouts/15/Doc.aspx?sourcedoc=%7BE6BEB28C-A745-4EF9-A93C-07433762D78C%7D&file=Netzwerktechnik.pptx&action=edit&mobileredirect=true&DefaultItemOpen=1&EntityRepresentationId=6d260c7b-8716-4001-9450-b838ce385f4c) [1](https://mthcloud-my.sharepoint.com/personal/michael_lindner_mth-it-service_com/_layouts/15/Doc.aspx?sourcedoc=%7BE6BEB28C-A745-4EF9-A93C-07433762D78C%7D&file=Netzwerktechnik.pptx&action=edit&mobileredirect=true&DefaultItemOpen=1)

## Netzwerkdienste

### DNS (Domain Name System)

- Wandelt Domainnamen in IP-Adressen um
- Zonen und Resource Records verwalten
- Integration in Active Directory möglich
- DNSSEC für Sicherheit

### DHCP (Dynamic Host Configuration Protocol)

- Automatische IP-Vergabe
- Unterstützt Failover-Konfigurationen (Load Balance, Hot Standby)
- Replikation von Lease-Informationen

Quelle: [WS-011T00A__M03](https://mthcloud-my.sharepoint.com/personal/michael_lindner_mth-it-service_com/_layouts/15/Doc.aspx?sourcedoc=%7B23467F61-8DFD-43E3-B507-41C16DB7E255%7D&file=WS-011T00A__M03.pptx&action=edit&mobileredirect=true&DefaultItemOpen=1&EntityRepresentationId=3955617f-2c9f-4aa5-be0b-c6f9e4e96f1b) [2](https://mthcloud-my.sharepoint.com/personal/michael_lindner_mth-it-service_com/_layouts/15/Doc.aspx?sourcedoc=%7B23467F61-8DFD-43E3-B507-41C16DB7E255%7D&file=WS-011T00A__M03.pptx&action=edit&mobileredirect=true&DefaultItemOpen=1)

## Netzwerkdesign und Dienste

- DNS/DHCP/LDAP auf dedizierten Servern
- Segmentierung in DMZ, Clientnetz und Verwaltungsnetz
- Dienste wie SMB, HTTPS, FTP über definierte Ports

Quelle: [Netzwerkplanung](https://mthcloud-my.sharepoint.com/personal/michael_lindner_mth-it-service_com/_layouts/15/Doc.aspx?sourcedoc=%7BAF550BDE-48B6-49B3-88ED-62B0D835B434%7D&file=Netzwerkplanung.docx&action=default&mobileredirect=true&DefaultItemOpen=1&EntityRepresentationId=4f389cf0-ab84-4794-935b-91822da4df85) [3](https://mthcloud-my.sharepoint.com/personal/michael_lindner_mth-it-service_com/_layouts/15/Doc.aspx?sourcedoc=%7BAF550BDE-48B6-49B3-88ED-62B0D835B434%7D&file=Netzwerkplanung.docx&action=default&mobileredirect=true&DefaultItemOpen=1)

## Lernpfade und Ressourcen

### 📚 Webartikel

- [OSI Modell einfach erklärt – Studyflix](https://studyflix.de/informatik/osi-modell-5524) [4](https://studyflix.de/informatik/osi-modell-5524)
- [OSI-Schichtenmodell verständlich erklärt – Dirks Computerecke](https://www.dirks-computerecke.de/netzwerk/osi-schichtenmodell-erklaert.htm) [5](https://www.dirks-computerecke.de/netzwerk/osi-schichtenmodell-erklaert.htm)

### 🎥 Videos

- [OSI SCHICHTENMODELL einfach erklärt (YouTube)](https://www.youtube.com/watch?v=_kDogzR0-4Q) [6](https://www.youtube.com/watch?v=_kDogzR0-4Q)
- [Netzwerktechnik Grundlagen #7 – OSI Modell erklärt](https://www.youtube.com/watch?v=PGKBko9veSw) [7](https://www.youtube.com/watch?v=PGKBko9veSw)
- [OSI Modell – Was ist das? (Takiry)](https://www.youtube.com/watch?v=xiTr5B19Zd4) [8](https://www.youtube.com/watch?v=xiTr5B19Zd4)

## Weiterführende Schulungen

- Webinar: *Administration von Windows Server 2022/2025* vom 25.–29.08.2025
  - Inhalte: Hyper-V, DNS, DHCP, Active Directory
  - Organisiert von [Michael Lindner - MTH IT Service](https://www.office.com/search?q=Michael+Lindner+-+MTH+IT+Service&EntityRepresentationId=42a8730d-2d5d-4bb8-a094-d12f787952f9) [9](https://teams.microsoft.com/l/meeting/details?eventId=AAMkAGYzNTE2NjJkLTUyMDQtNDk4MC1iNGZjLTIzYmZhNmMyY2VhYwFRAAgI3eaO-1VAAEYAAAAAUJ2OcHVP70CA432YSdgAaAcAaWLmTufbFE63SKrINsWuLgAAAPbmXwAA2u4dEmi-sk_5tBFU84UypgAKgCfw1gAAEA%3d%3d)
  - Kontakt: [michael.lindner@mth-it-service.com](mailto:michael.lindner@mth-it-service.com)

---

> Dieses Dokument richtet sich an Administratoren, die mit Windows Server arbeiten und ein solides Netzwerkverständnis aufbauen möchten.


