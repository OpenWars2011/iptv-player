# IPTV Player

Ein kostenloser IPTV-Player für Windows, der lokal auf deinem PC läuft.

- Über 24.000 frei verfügbare Sender und Radios, sortiert nach Land, Sprache und Art
- TV-Programm für tausende Sender, eigene XMLTV-Quellen möglich
- Live-Ergebnisse aus 15 Sportarten mit Tabellen, dazu Sport-News aus 18 Quellen
- Sender-Check, der zeigt, welche Sender gerade laufen
- Zugriff vom Handy oder Smart-TV im eigenen WLAN, mit Login

## Download

Die aktuelle Version liegt unter **[Releases](../../releases/latest)** als `IPTV-Player.zip`.

## Installation

1. [Node.js](https://nodejs.org) (LTS) installieren.
2. `IPTV-Player.zip` entpacken und den Ordner an einen festen Ort legen.
3. `IPTV Player.exe` doppelklicken. Bei „Der Computer wurde geschützt“ auf „Weitere Informationen“ und „Trotzdem ausführen“ klicken (das Programm ist nicht signiert).
4. Im Browser unter „Registrieren“ ein Konto anlegen.
5. Optional: `Autostart einrichten.vbs` doppelklicken.

## Voraussetzungen

Windows 10 oder 11, Node.js 18 oder neuer, ein aktueller Browser (Chrome, Edge oder Firefox).

## Hinweis

Der Player enthält keine Sendungen. Er spielt nur Streams ab, die die Anbieter frei ins Internet stellen, und lädt dafür öffentliche Senderlisten (u. a. [Free-TV/IPTV](https://github.com/Free-TV/IPTV) und [iptv-org](https://github.com/iptv-org/iptv)). Manche Sender sind nur in ihrem Land empfangbar oder zeitweise offline; kopiergeschützte Sender öffnen den offiziellen Player des Anbieters.

Du bist selbst dafür verantwortlich, die Nutzungsbedingungen der Sender und die Gesetze in deinem Land einzuhalten. Sportdaten stammen aus öffentlichen Schnittstellen (ESPN, OpenLigaDB), News aus den RSS-Feeds der jeweiligen Redaktionen.

## Lizenz

MIT, siehe [LICENSE](LICENSE).
