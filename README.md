# Gesprächsleitfaden für den Telefonassistenten



**Das Video zeigt die Lösung:** [demo.mp4](docs/demo.mp4), etwa 2 Minuten. Dieses Repo enthält die
Grundlage dazu. Showroom ADH, Stand 03.12.2026. Firma, Personen und Zahlen im Beispiel sind erfunden.

## Ausprobieren

`index.html` per Doppelklick öffnen. Kein Build, kein Server, keine Installation. Alle Eingaben
bleiben im Browserfenster.

1. `index.html` per Doppelklick öffnen. Oben liegen zwei Tickets aus Beispielanrufen.
2. Probeanruf „Supermarkt, Tiefkühlung ausgefallen“ führen. Der Assistent sagt zuerst, dass er ein KI-Assistent ist, fragt nur die fehlenden Angaben und gibt den Anruf an die Bereitschaft. Es entsteht T-103.
3. Als Jonas Weber anmelden und T-103 übernehmen.
4. Probeanruf „Hotel, Beschwerde“ führen: geht an die Leitung Kundendienst.
5. Als Sophie Albrecht die Regel zur Beschwerde abschalten. Ein Probeanruf fällt durch, die Freigabe ist gesperrt.
6. Regel wieder einschalten, bei der Störung „Seit wann“ abwählen. Alle Probeanrufe bestehen, Albrecht kann trotzdem nicht freigeben.
7. Als Andreas Keller freigeben. Die Anweisung an den Assistenten zeigt die neue Fassung.

## In zwei Minuten prüfen

| Schritt | Erwartet |
|---|---|
| Seite öffnen | Tickets offen 1, bei der Bereitschaft 0, Probeanrufe 5 von 5, Fassung 3, Stand frei |
| Probeanruf Supermarkt | drei Rückfragen (Anlage, seit wann, Rückruf), geht an Bereitschaft, sofort, Ticket T-103, Kacheln 2 und 1 |
| Probeanruf Feinkost | geht an Buchhaltung, Hinweis „unvollständig: Rechnungsnummer“ |
| Probeanruf Stadtküche | Notruf wird genannt, geht an Bereitschaft, vier Rückfragen |
| T-103 als Sophie Albrecht übernehmen | Meldung, dass das Ticket bei Jonas Weber liegt |
| Haken „nicht erreichbar“ setzen | T-103 liegt bei Sven Krause |
| Regel zur Beschwerde abschalten (als Albrecht) | Fassung 4, Entwurf, 4 von 5, „Hotel, Beschwerde“ durchgefallen, landet bei Disposition |
| Freigeben | „Nicht bestanden: Hotel, Beschwerde.“ |
| Regel wieder ein, freigeben als Albrecht | „Wer den Leitfaden geändert hat, gibt ihn nicht frei.“ |
| Freigeben als Keller | Fassung 4 freigegeben, Eintrag im Protokoll |
| Regel „KI-Assistent“ | Haken lässt sich nicht entfernen |

## Grenzen

- Im Browser geöffnet und an den Kennzahlen der Beispieldaten geprüft. Im Alltag nicht erprobt.


## Rechte

Alle Rechte vorbehalten, Alf-David Heermann 2026. Der Quelltext ist zum Ansehen und Ausprobieren
veröffentlicht. Kontakt: https://www.linkedin.com/in/alf-david-heermann
