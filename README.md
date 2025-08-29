## 202535
# Weindows Server 2025 Administrator Grundlagen

> Trainer Michael Lindner

# 📘 Windows Server 2025 Administration

## 🧠 Thema: Wichtige Grundlagen
Dieser Leitfaden dient als Vorbereitung, um die Server-Dienste von Windows Server 2025 besser zu verstehen. Er behandelt essenzielle Netzwerk- und Sicherheitskonzepte sowie die Verwaltung von Dienstkonten.

---

## 🧩 OSI-Schichtenmodell
Das **OSI-Modell (Open Systems Interconnection)** ist ein Referenzmodell für Netzwerkprotokolle und besteht aus sieben Schichten:

| Schicht | Name                | Funktion |
|--------|---------------------|----------|
| 1      | Bitübertragung      | Physikalische Übertragung von Daten über Medien |
| 2      | Sicherung           | Fehlererkennung und -behebung, MAC-Adressen |
| 3      | Vermittlung         | Routing, IP-Adressen |
| 4      | Transport           | Zuverlässige Datenübertragung (TCP/UDP) |
| 5      | Sitzung             | Verwaltung von Sitzungen zwischen Anwendungen |
| 6      | Darstellung         | Datenformatierung, Verschlüsselung |
| 7      | Anwendung           | Schnittstelle zur Benutzeranwendung |

🔗 [Lernpfad zum OSI-Modell](https://learn.microsoft.com/de-de/shows/networking-fundamentals/02)

---

## 🔐 PKI – Public Key Infrastructure
Die **PKI** ermöglicht sichere Kommunikation durch:
- Digitale Zertifikate
- Verschlüsselung
- Authentifizierung

Sie besteht aus:
- Zertifizierungsstellen (CA)
- Öffentlichen und privaten Schlüsseln
- Vertrauensketten

🔗 [Grundlagen zu Microsoft Cloud PKI](https://learn.microsoft.com/de-de/intune/intune-service/protect/microsoft-cloud-pki-fundamentals)

---

## 🌐 Netzwerk: IPv4 und IPv6
### IPv4
- 32-Bit Adressen (z. B. 192.168.1.1)
- Begrenzter Adressraum

### IPv6
- 128-Bit Adressen (z. B. 2001:db8::1)
- Erweiterter Adressraum für moderne Netzwerke

Beide Protokolle sind essenziell für die Kommunikation in lokalen und globalen Netzwerken.

🔗 [IPv4/IPv6 Lernmodul](https://learn.microsoft.com/en-us/training/modules/configure-ip-network-connectivity/)

---

## 🖧 Netzwerkgeräte
Netzwerkgeräte sind die Bausteine jeder IT-Infrastruktur:
- **Router**: Verbinden Netzwerke und leiten Datenpakete weiter
- **Switches**: Verteilen Daten innerhalb eines Netzwerks
- **Firewalls**: Kontrollieren den Datenverkehr und schützen vor Angriffen
- **Access Points**: Ermöglichen drahtlosen Zugriff auf Netzwerke

🔗 [Netzwerkgeräte und Grundlagen](https://learn.microsoft.com/de-de/training/modules/network-fundamentals/)

---

## 👤 Managed Service Accounts (MSA)
MSAs vereinfachen die Verwaltung von Dienstkonten:
- Automatische Passwortverwaltung
- Höhere Sicherheit durch eingeschränkten Zugriff
- Unterstützung für Gruppen-Managed Service Accounts (gMSA)
- Neu in Windows Server 2025: Delegated Managed Service Accounts (dMSA)

🔗 [Delegated Managed Service Accounts in Windows Server 2025](https://learn.microsoft.com/en-ca/windows-server/identity/ad-ds/manage/delegated-managed-service-accounts/delegated-managed-service-accounts-overview)

---

## 🎓 Lernpfade für Windows Server 2025
- [Windows Server 2025 Lernpfad auf Microsoft Learn](https://learn.microsoft.com/de-de/training/windows-server/)
- [Was ist neu in Windows Server 2025](https://learn.microsoft.com/en-us/windows-server/get-started/whats-new-windows-server-2025)
- [Windows Server Summit 2025](https://techcommunity.microsoft.com/event/techcommunitylive/windows-server-summit-2025/4361618)

---

📌 **Hinweis:** Dieser Leitfaden ist als Einstieg gedacht. Für praktische Übungen und Zertifizierungen empfiehlt sich die Nutzung der Microsoft Learn Plattform.
