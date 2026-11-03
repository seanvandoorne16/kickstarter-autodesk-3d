# Spoelboek

Een webtool om per filamentspoel je slicerinstellingen bij te houden en de [FDM-testprint](../FDM-protocol/README.md) te scoren volgens het protocol van Kickstarter x Autodesk.

**Online gebruiken:** `https://seanvandoorne16.github.io/kickstarter-autodesk-3d/tool/`

**Lokaal gebruiken:** download `index.html` en open het bestand in je browser. Je hoeft niets te installeren.

## Wat de tool doet

- Spoelen beheren: merk, materiaal, kleur en notities.
- Instellingen per spoel bijhouden. De namen zijn dezelfde als in Bambu Studio (Nozzle temperature, Flow ratio, X-Y hole compensation, Bridge flow, ...).
- De zeven tests van het protocol scoren, met een totaal op 30. Voor maatnauwkeurigheid vul je de metingen in en rekent de tool de score zelf uit.
- Advies per test die niet goed scoort, met knoppen die de aanpassing meteen in je instellingen zetten.
- Historiek: elke test bewaart de instellingen van dat moment, zodat je ziet welke wijziging het verschil maakte.

## Opslag

Je gegevens staan alleen in je eigen browser (localStorage), op deze computer. Er gaat niets naar een server. Gebruik **Exporteren** voor een back-up of om je gegevens naar een ander toestel over te zetten, en **Importeren** om ze terug te laden. Als je je browsergegevens wist, ben je alles kwijt zonder export.

## Opmerkingen

- De scoring volgt [FDM-protocol/README.md](../FDM-protocol/README.md). Het advies zijn vuistregels om mee te beginnen, geen deel van het protocol.
- Het protocol is bedoeld om printers te vergelijken met één vaste filament (eSun PLA+). Gebruik je de test om per spoel te tunen, vergelijk dan alleen scores van dezelfde spoel.
- Ringing (test 6) en het Z-patroon (test 7) zijn meestal mechanisch en los je niet op in de slicer.

## Licentie

Deze map is een toevoeging aan een fork van [kickstarter/kickstarter-autodesk-3d](https://github.com/kickstarter/kickstarter-autodesk-3d) en valt onder dezelfde Apache License 2.0 (zie `LICENSE.txt` in de root). Het testmodel en het protocol zijn van Kickstarter en Autodesk.
