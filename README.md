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
- **Spara som HTML‑fil** – laddar ner appen med all data inbakad i en enda fil; öppnas var som helst, helt offline. Bästa sättet att spara och bevara sitt arbete.
- **Export/import (JSON)** – extra säkerhetskopior och delning. Sker helt lokalt via filer.

## Viktigt om data

- Data lagras automatiskt i webbläsarens lokala lagring – men rensar du webbläsardata försvinner planerna.
- **Spara regelbundet med knappen "Spara som HTML‑fil"** (uppe till höger). Den laddar ner en ny kopia av appen med **all din data inbakad i själva filen**. Filen blir din huvudkopia: dubbelklicka på den så öppnas appen med allt innehåll, även på en annan dator.
- Knappen "Exportera" ger en JSON‑backup, och "Importera" läser in sådana filer – bra för extra säkerhetskopior eller delning.

### Arbetsflöde för den som gör ändringar i filen

1. Öppna din senaste sparade HTML‑fil och arbeta i appen.
2. Klicka "💾 Spara som HTML‑fil" när du är klar – du får en ny fil med alla ändringar.
3. Filnamnet innehåller kommun och datum, så du kan spara versionsvis och ladda upp den senaste filen till detta repo.

## Utskrift

Öppna en beredskapsplan och klicka "Skriv ut planen" – papperskopian kan förvaras i jourhytten/bilen. Menyer och knappar utelämnas automatiskt vid utskrift.
