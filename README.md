# VA‑Beredskap – Beredskapsplaner för kommunala VA‑anläggningar

En offline-app i en enda HTML‑fil som hjälper kommunen att upprätta och underhålla beredskapsplaner för VA‑anläggningar (pumpstationer, ledningar, reningsverk/vattenverk, brunnar m.m.).

## Kom igång

1. Ladda ner `index.html`.
2. Dubbelklicka på filen – den öppnas i valfri modern webbläsare (Chrome, Edge, Firefox). Ingen installation eller internetuppkoppling krävs.
3. All data sparas lokalt i webbläsaren (localStorage) på den dator du använder.

## Funktioner

- **Översikt** – statistik per typ, antal planer och prioritering, kommunnamn.
- **Anläggningar** – register med typ (pumpstation, VA‑ledning, verk, brunn), kritisk prioritet, plats/koordinat, antal anslutna hushåll, berörda verksamheter och teknisk beskrivning.
- **Beredskapsplaner** – en plan per anläggning med riskbedömning (sannolikhet/konsekvens/nivå), åtgärder vid driftstörning i prioritetsordning med ansvarig och tidsgräns, resurser/kontakter, revisionsnummer, godkännare och utskriftsvänlig layout.
- **Kontaktregister** – jourer, el‑PAT, entreprenörer, leverantörer, tankbilar m.m., som kan kopieras rakt in i planerna.
- **Beredskapschecklistor** – färdiga mallar ("Vid driftstörning", "Vid elavbrott/pumpstörning", "Vid ledningsbrott") som kan kryssas av vid övning eller skarpt läge.
- **Övningar & händelselog** – logga övningar och verkliga händelser med uppföljning in i planerna.
- **Export/import (JSON)** – säkerhetskopiera, dela eller flytta data mellan datorer. Sker helt lokalt via filer.

## Viktigt om data

- Data ligger bara i webbläsarens lokala lagring – rensar du webbläsardata försvinner planerna.
- **Exportera regelbundet** en JSON‑säkerhetskopia (knappen "Exportera" uppe till höger).
- För att flytta data till en annan dator: exportera filen och använd "Importera" på den andra datorn.

## Utskrift

Öppna en beredskapsplan och klicka "Skriv ut planen" – papperskopian kan förvaras i jourhytten/bilen. Menyer och knappar utelämnas automatiskt vid utskrift.
