Bolånejakten 🏠
Webbtjänst som jämför bolåneräntor mot storbankerna och beräknar din besparingspotential.
🌐 Live: bolanejakten.se  
🤖 AI-version: bolanejakten.se/ai-app
---
Om projektet
Bolånejakten är ett verktyg för svenska bolånetagare som vill veta om de betalar för mycket i ränta. Användaren matar in sitt lån — eller laddar upp sitt amorteringsunderlag som PDF — och får en jämförelse mot Swedbank, SEB, Handelsbanken, Nordea, SBAB och Länsförsäkringar, samt ett AI-genererat förhandlingsbrev att skicka till banken.
Typisk kund sparar 10 000–25 000 kr per år efter att ha använt tjänsten.
---
Två versioner
Version 1 — Manuell jämförelse (bolanejakten.se)
Användaren fyller i lånebelopp, ränta och bank. Appen jämför mot 6 storbanker och genererar ett förhandlingsskript.
Version 2 — AI-driven (bolanejakten.se/ai-app)
Användaren laddar upp sitt amorteringsunderlag som PDF eller bild. Claude AI:
Läser och tolkar dokumentet automatiskt
Extraherar lånebelopp, ränta, bank och bindningstid
Jämför mot aktuella marknadsräntor
Genererar ett personligt förhandlingsbrev anpassat till kundens situation
---
Funktioner
📄 PDF/bilduppladdning med AI-extraktion
📊 Realtidsjämförelse mot 6 storbanker
💰 Besparingsberäkning per år och månad
✍️ AI-genererat förhandlingsbrev (Claude API)
📋 Kopiera och skicka direkt till banken
📱 Mobilanpassad och responsiv design
🔒 Ingen datalagring — allt beräknas lokalt i webbläsaren
⚡ Swish-betalning (79 kr per jämförelse)
🛠 Admin-panel för att uppdatera räntor utan kod
---
Teknik
Frontend: Vanilla HTML, CSS, JavaScript (inga ramverk)
AI: Anthropic Claude API (claude-sonnet-4) för dokumentanalys och brevgenerering
Hosting: Netlify
Domän: bolanejakten.se
Design: Custom CSS med CSS-variabler, Google Fonts (DM Serif Display + DM Sans)
Betalning: Swish Handel (integreras vid lansering)
---
Filer
Fil	Beskrivning
`index.html`	Landningssida med hero, kundcitat och prissättning
`app.html`	Manuell jämförelseapp — 3-stegsflöde
`ai-app.html`	AI-driven version med PDF-uppladdning och brevgenerering
`admin.html`	Admin-panel för räntuppdateringar och statistik
`privacy.html`	Integritetspolicy (GDPR-anpassad)
---
Kom igång lokalt
Inga beroenden eller installationer behövs:
```bash
git clone https://github.com/Fraxinus87/bolanejakten.git
cd bolanejakten
open index.html        # Landningssida
open app.html          # Manuell app
open ai-app.html       # AI-version
```
---
Roadmap
[x] MVP med manuell inmatning
[x] Bankjämförelse mot 6 storbanker
[x] Förhandlingsskript
[x] Live på egen domän (bolanejakten.se)
[x] AI-driven version med PDF-uppladdning
[x] AI-genererat förhandlingsbrev
[ ] Riktig Swish Handel-integration
[ ] E-postrapport via Mailgun
[ ] BankID-integration för automatisk datahämtning
[ ] Automatisk ränteskrapning (daglig uppdatering)
[ ] Prenumerationsmodell — "Bevaka din ränta"
---
Kontakt
📧 hej@bolanejakten.se  
🌐 bolanejakten.se
---
Bolånejakten är ett informationsverktyg — inte finansiell rådgivning. Kontakta alltid banken för bindande erbjudande.
