# DNS-Filterlisten (Blocklisten)

- In diesem Repository sind einige Blocklisten, zusammengestellt für Pi hole.
- Die Zusammenstellung basiert auf persönlicher Erfahrung.

## Weitere Blocklisten & Empfehlungen
- Für Empfehlungen zu Blocklisten und Hinweise, wie man selbst eigene Blocklisten erstellen kann, sind in der [Anleitung zu Pi-hole](https://github.com/replay45/Linux-RaspberryPI-NextCloud/tree/main/raspberry-pi) zu finden.

--------------------------------------------------------------------------

## Pi hole
- Die Installation & Einrichtung von Pi hole, wird ebenfalls in der [Anleitung zu Pi-hole](https://github.com/replay45/Linux-RaspberryPI-NextCloud/tree/main/raspberry-pi) gezeigt.
- Dort finden sich auch weitere Informationen zum DNS-Server, den DNS-Filterlisten und dem [Raspberry Pi](https://www.raspberrypi.com/).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Disclaimer
Alle folgenden Informationen und Anleitungen in diesem Repository sind ausschließlich für ethical Hacking und Bildungszwecke !
Die Informationen und Anleitungen sind verantwortungsbewusst und nur für legale Zwecke zu nutzen.
Alle Inhalte dienen nur der allgemeinen Information und stellen KEINE fachliche oder rechtliche Beratung dar!
Das Befolgen der Anleitungen, das Ausführen von Befehlen, von Code, sowie Skripten und das Besuchen von verlinkten Webseiten Dritter, erfolgt auf eigenes Risiko.
Der Autor übernimmt keine Garantie für die Vollständigkeit und Korrektheit der Inhalte und haftet nicht für entstandene Schäden.
Die Nutzung von Funkfrequenzen (RF) unterliegt den Gesetzen des jeweiligen Landes.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## DNS-Filterlisten (Blocklisten) in Pi hole hinzufügen
- Text-Datei aus diesem Repository öffnen
- Auf der rechten Seite auf `Raw` klicken und URL kopieren
- Pi hole Dashboard öffnen
- Unter `Lists` die URL einfügen und `Add blocklist` auswählen
- Nun unter `Tools` `Update Gravity` ausführen, um Listen zu aktualisieren

## Status von Blocklisten einsehen
- Unter `Lists` kann der Status der einzelnen Listen eingesehen werden
  - Eine Liste auswählen, und prüfen, ob eine Zahl hinter `Number of entries` steht.
  - Hinter `Number of non-domains` sollte idealerweise `0` stehen.

--------------------------------------------------------------------------
