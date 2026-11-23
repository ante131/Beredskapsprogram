# VA‑Beredskap – Beredskapsplan för kommunens VA

En offline-app i en enda HTML-fil som hjälper kommunen att ta fram en komplett VA‑beredskapsplan – genomförd som **checklista + mall + bibliotek**, så att ingen del glöms bort.

Underlaget bygger på dokumentet *Mall och checklista – VA‑beredskapsplan för Uppvidinge kommun*: appen innehåller hela dess Del 1 (arbetschecklistan), Del 2 (dokumentmallen) och Del 3 (källorna).

## Kom igång

1. Ladda ner `index.html` och dubbelklicka – den öppnas i valfri modern webbläsare (Chrome, Edge, Firefox). Ingen installation eller internetuppkoppling krävs.
2. All data sparas lokalt i webbläsaren (localStorage) på den dator du använder.
3. Börja på **Översikten**: den visar alltid *”Din nästa uppgift”* – följ den hela vägen till en färdig plan.

## Funktioner

- **Översikt** – övergripande status och påminnelser: projektchecklistan, planmallens avsnitt, händelseplaner, anläggningar m.m. Visar alltid nästa uppgift i arbetet.
- **Projektchecklista** (mallens Del 1) – 31 punkter i fem faser: förarbete, kartläggning av systemet, risk- och sårbarhetsanalys, handlingsplaner/åtgärder, samråd/beslut/övning. Varje punkt har ett 💡-tips som pekar till rätt ställe i appen. Progress i procent.
- **Anläggningar** – inventering enligt mallens tabell (avsnitt 5): råvatten, kapacitet, reservoarvolym, drifttid vid produktionsstopp, reservkraft, antal abonnenter, kritiska abonnenter. Tabellen byggs automatiskt in i planmallen.
- **Planmall** (mallens Del 2) – alla 14 avsnitt + försättsblad. Varje avsnitt har: en gul instruktionsruta som förklarar exakt vad som ska skrivas, en skrivruta och en ”Klar”-kryss. Gällande lagtext (avsnitt 2) kan infogas med ett klick som standardtext. Utskrift ger en utskriftsvänlig plan.
- **Händelseplaner** (mallens avsnitt 7) – hotlistans 8 händelser är förifyllda (vattenverkshaveri, kokvattenmisstanke, ledningsbrott, kemikaliebrist, IT‑angrepp, personalbortfall, avloppsstopp, höjd beredskap). Varje händelseplan har mallens fasta struktur: kort beskrivning → Larma → Åtgärd första timmarna → Åtgärd vid längre avbrott → Information → Rapportering → Återgång till normal drift. Påbörjade planer markeras gröna.
- **Kontakter** (bilaga 1) – jourer, el-PAT, entreprenörer, leverantörer, tankbilar, myndigheter. Varje kontakt kan ha en ”register-text” att klistra in rakt i planen (roller, samarbeten). Telefonlista kan skrivas ut.
- **Övningar & händelselog** (avsnitt 12 och 14) – logga övningar och verkliga händelser, och markera om de ledde till ändringar i planen.
- **Bibliotek** (mallens Del 3) – källor och underlag (MSB, Livsmedelsverket, Svenskt Vatten, SOU 2024:82 m.fl. med länkar), tumregler att använda i planen (3–5 l/pers/dygn, 72‑timmarsbudskapet m.m.) och färdiga informationstexter (kokvatten, avloppsstörning, nödvatten, planerat avbrott) att kopiera.
- **Spara som HTML‑fil** – laddar ner appen med all data inbakad i en enda fil; öppnas var som helst, helt offline. Bästa sättet att spara och bevara sitt arbete.
- **Export/import (JSON)** – extra säkerhetskopior och delning.

## Viktigt om data

- All data lagras automatiskt lokalt i webbläsaren – men rensar du webbläsardata försvinner arbetet.
- **Spara regelbundet med ”💾 Spara som HTML‑fil”** (uppe till höger). Filen blir din huvudkopia: dubbelklicka på den så öppnas appen med allt innehåll, även på en annan dator. Filnamnet innehåller kommun och datum.
- Knappen ”Exportera” ger en JSON‑backup, och ”Importera” läser in sådana filer.
- **Sekretess:** mallen påpekar att avsnitt 9 (höjd beredskap) kan behöva skyddsvärderas – håll i så fall den delen i separat dokument med begränsad spridning.

## Workflow

1. Öppna din senaste sparade HTML‑fil och arbeta i appen.
2. Följ checklistan; skriv mallavsnitt och händelseplaner allteftersom.
3. Klicka **💾 Spara som HTML‑fil** när du är klar – du får en ny fil med alla ändringar.
4. Ladda gärna upp den senaste filen till detta repo som versionshantering.
