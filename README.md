# IPTV Player

Ein kostenloser IPTV-Player für Windows, der lokal auf deinem PC läuft.

- Über 24.000 frei verfügbare Sender und Radios, sortiert nach Land, Sprache und Art
- TV-Programm für tausende Sender, eigene XMLTV-Quellen möglich
- Mit einem Klick auf den Fernseher senden: Chromecast, Google TV oder Smart-TVs mit DLNA
- Live-Ergebnisse aus 15 Sportarten mit Tabellen, dazu Sport-News aus 18 Quellen
- Sender-Check, der zeigt, welche Sender gerade laufen
- Zugriff vom Handy im eigenen WLAN, mit Login

## Download

Unter **[Releases](../../releases/latest)**:

- **`IPTV-Player-Setup.exe`** – Installer (empfohlen). Node.js ist enthalten, keine Administratorrechte nötig.
- `IPTV-Player.zip` – Version ohne Installation, braucht [Node.js](https://nodejs.org).

## Installation

1. `IPTV-Player-Setup.exe` herunterladen und starten. Bei „Der Computer wurde geschützt“ auf „Weitere Informationen“ und „Trotzdem ausführen“ klicken (das Programm ist nicht signiert).
2. „Installieren“ klicken. Optional: Desktop-Verknüpfung und Start mit Windows.
3. Der Player öffnet sich im eigenen Fenster. Unter „Registrieren“ ein Konto anlegen.

Deinstallieren: Windows-Einstellungen → Apps → IPTV Player.

## Auf den Fernseher senden

Beim laufenden Sender auf **📺 Auf TV** klicken. Beim ersten Mal den WLAN-Zugriff einschalten und in der Windows-Firewall „Zugriff zulassen“ (private Netzwerke) wählen. Der Fernseher bekommt eine zeitlich begrenzte Adresse, die nur den Stream freigibt.

## Voraussetzungen

Windows 10 oder 11, Microsoft Edge oder Google Chrome. Für das Senden: Chromecast, Google TV oder ein DLNA-fähiger Smart-TV im selben WLAN.

## Hinweis

Der Player enthält keine Sendungen. Er spielt nur Streams ab, die die Anbieter frei ins Internet stellen, und lädt dafür öffentliche Senderlisten (u. a. [Free-TV/IPTV](https://github.com/Free-TV/IPTV) und [iptv-org](https://github.com/iptv-org/iptv)). Manche Sender sind nur in ihrem Land empfangbar oder zeitweise offline; kopiergeschützte Sender öffnen den offiziellen Player des Anbieters.

Du bist selbst dafür verantwortlich, die Nutzungsbedingungen der Sender und die Gesetze in deinem Land einzuhalten. Sportdaten stammen aus öffentlichen Schnittstellen (ESPN, OpenLigaDB), News aus den RSS-Feeds der jeweiligen Redaktionen. Der Installer enthält [Node.js](https://nodejs.org) (MIT-Lizenz).

## Lizenz

MIT, siehe [LICENSE](LICENSE).
