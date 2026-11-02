# Tests und Reproduzierbarkeit — Chiptune Demoscene / Rastergarten

## Voraussetzungen
Node 22+; Browser mit Web Audio.

## Befehle
```text
npm test
```

Start/Build: Für die gemeinsame Anwendung Audio Lab verwenden. Historische eigenständige Demo: npm start.

## Tatsächlicher Befund vom 02.11.2026
1 Timingtest bestanden. Audio-Lab-Integration hat gesonderte Browser-/Historiensicherungsnachweise. Kein neuer subjektiver Hörtest.

Bei fehlenden Paketen/Hardware/Betriebssystemen ist das Ergebnis „nicht ausgeführt“, kein Pass. Plattformnachweise aus älteren Detailberichten gelten nur für die dort genannten Versionen. Android-Automatisierung ausschließlich mit expliziter emulator-Seriennummer und bestätigtem ro.kernel.qemu=1. Physische Geräte, persönliche Medien und Produktionskonten sind keine Testfixtures.

## Vor Merge
`git diff --check` ausführen; relevante Funktionstests wiederholen, wenn Codeänderungen ihren Befund entwerten. Speicherdaten/alte Versionen erhalten. Fehlende externe Abnahmen in HANDOFF.md benennen.
