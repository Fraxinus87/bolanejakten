Bolånejakten 🏠
Webbtjänst som jämför bolåneräntor mot storbankerna och beräknar din besparingspotential.
🌐 Live: bolanejakten.se
---
Om projektet
Bolånejakten är ett verktyg för svenska bolånetagare som vill veta om de betalar för mycket i ränta. Användaren matar in sitt lån och får en jämförelse mot Swedbank, SEB, Handelsbanken, Nordea, SBAB och Länsförsäkringar — med ett färdigt förhandlingsskript att ringa banken med.
Typisk kund sparar 10 000–25 000 kr per år efter att ha använt tjänsten.
---
Funktioner
📊 Realtidsjämförelse mot 6 storbanker
💰 Besparingsberäkning per år och månad
📋 Personligt förhandlingsskript
📱 Mobilanpassad och responsiv design
🔒 Ingen datalagring — allt beräknas lokalt i webbläsaren
⚡ Swish-betalning (79 kr per jämförelse)
🛠 Admin-panel för att uppdatera räntor utan kod
---
Teknik
Frontend: Vanilla HTML, CSS, JavaScript (inga ramverk)
Hosting: Netlify (CD/CI via drag-and-drop deploy)
Domän: bolanejakten.se via Loopia DNS
Design: Custom CSS med CSS-variabler, Google Fonts (DM Serif Display + DM Sans)
Betalning: Swish Handel (integreras vid lansering)
---
Filer
Fil	Beskrivning
`index.html`	Landningssida med hero, kundcitat och prissättning
`app.html`	Huvudappen — 3-stegsflöde för jämförelse
`admin.html`	Admin-panel för räntuppdateringar och statistik
`privacy.html`	Integritetspolicy (GDPR-anpassad)
---
Skärmdumpar
Landningssida
Tydligt värdeerbjudande med exempelresultat och kundberättelser.
Jämförelseapp
Tre steg: mata in lån → betala → få rapport med bankjämförelse och förhandlingsskript.
Admin-panel
Uppdatera bankräntor, se transaktioner och hantera inställningar utan kod.
---
Roadmap
[x] MVP med manuell inmatning
[x] Bankjämförelse mot 6 storbanker
[x] Förhandlingsskript
[x] Live på egen domän
[ ] Riktig Swish Handel-integration
[ ] E-postrapport via Mailgun
[ ] BankID-integration för automatisk datahämtning
[ ] Automatisk ränteskrapning (daglig uppdatering)
[ ] Prenumerationsmodell — "Bevaka din ränta"
---
Kom igång lokalt
Inga beroenden eller installationer behövs — öppna bara filerna direkt i webbläsaren:
```bash
git clone https://github.com/Fraxinus87/bolanejakten.git
cd bolanejakten
open index.html
```
---
Kontakt
📧 hej@bolanejakten.se  
🌐 bolanejakten.se
---
Bolånejakten är ett informationsverktyg — inte finansiell rådgivning. Kontakta alltid banken för bindande erbjudande.
