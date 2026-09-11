# Examen 1 Grupparbete - Grupp 10
## Gruppen
Ihab Abdul Satar Hussein,
Johan Svensson,
Louie Al-Saffar

## Examination 1 (Eventsidan) :
    1. Hero — namn, bild/logotyp, datum, plats, kort beskrivning
    2. Schema — CSS Grid (se 06-css-grid)
    3. Highlights — Flexbox
    4. Nav + footer — ankare till sektioner; sidfot med kontakt + fiktiva sponsorer
    5. Responsivitet — @media; testa viewport så layouten inte går sönder

## README tre frågor: semantik, arv, Flex vs Grid (motivera från er kod).
GitHub: gemensamt repo, synliga commits från alla (samma dator → namn i meddelandet).
Inlämning fredag 11 september (länk till repot i Moodle).


1. Vad innebär semantisk HTML och varför har ni använt det på er eventsida?

svar: Semantisk HTML innebär att man använder HTML‑element som beskriver innehållets funktion, till exempel <header>, <nav>, <main>, <section> och <footer>. Det gör sidan mer strukturerad, lättare att förstå för både webbläsare och skärmläsare, och förbättrar tillgänglighet och SEO. På vår eventsida har vi använt semantisk HTML för att skapa en tydlig och logisk struktur, göra sidan mer tillgänglig för personer med funktionsnedsättning, hjälpa sökmotorer att tolka innehållet korrekt och göra koden enklare att underhålla och bygga vidare på.


2. Hur fungerar arv i CSS? Ge ett exempel från er egen kod.

svar: Arv i CSS innebär att vissa egenskaper automatiskt förs vidare från ett föräldraelement till dess barn. Det gäller främst textegenskaper som font‑family, color och line‑height. På vår eventsida använder vi arv genom att sätta font-family på body. Alla element inuti body, som rubriker, paragrafer och länkar, ärver denna font automatiskt. Det gör koden renare, kortare och enklare att underhålla.

3. Vad är den största skillnaden mellan Flexbox och CSS Grid, och när ska man använda vilket verktyg? Motivera utifrån hur ni fördelade dem på er sida.

svar: Flexbox är Layout i en riktning (rad eller kolumn). Perfekt för menyer, knapprader, kortband, centering.
CSS Grid är Layout i två riktningar (rader och kolumner). Perfekt för tabeller, dashboards, sidstrukturer, bildgallerier.
