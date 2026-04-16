Bolånejakten 🏠
Komplett webbtjänst för svenska bolånetagare — jämför räntor, få AI-analys och bevaka marknaden automatiskt.
🌐 Live: bolanejakten.se  
🤖 AI-version: bolanejakten.se/ai-app  
🔔 Räntebevakning: bolanejakten.se/bevaka
---
Om projektet
Bolånejakten hjälper svenska bolånetagare att sluta betala för mycket i ränta. Tjänsten har tre delar: en snabb manuell jämförelse, en AI-driven analys som läser ditt eget dokument, och en prenumerationstjänst som bevakar räntan åt dig och mejlar när det finns pengar att spara.
Typisk kund sparar 10 000–25 000 kr per år efter att ha använt tjänsten.
---
Tre produkter
1. Manuell jämförelse — bolanejakten.se/app
Fyll i lånebelopp, ränta och bank. Jämförelse mot 6 storbanker + förhandlingsskript. 79 kr engång.
2. AI-analys — bolanejakten.se/ai-app
Ladda upp ditt amorteringsunderlag som PDF eller bild. Claude AI extraherar dina uppgifter automatiskt, jämför mot marknaden och skriver ett personligt förhandlingsbrev. 79 kr engång.
3. Räntebevakning — bolanejakten.se/bevaka
Ange din ränta en gång. Vi kontrollerar bankernas räntor varje vecka och mejlar dig bara när det faktiskt lönar sig att agera. 29 kr/mån, första månaden gratis.
---
Funktioner
📄 PDF/bilduppladdning med AI-extraktion (Claude API)
📊 Realtidsjämförelse mot 6 storbanker
💰 Besparingsberäkning per år och månad
✍️ AI-genererat personligt förhandlingsbrev
🔔 Automatisk räntebevakning med mejlnotis
📋 Prenumerantdashboard med månadsintäkt
📱 Mobilanpassad och responsiv design
🔒 Ingen datalagring utan samtycke
⚡ Swish-betalning
🛠 Admin-panel för räntuppdateringar
---
Teknik
Frontend: Vanilla HTML, CSS, JavaScript — inga ramverk
AI: Anthropic Claude API (claude-sonnet-4) för dokumentanalys och brevgenerering
Hosting: Netlify (gratis tier)
Domän: bolanejakten.se via Loopia DNS
Design: Custom CSS, Google Fonts (DM Serif Display + DM Sans)
Lagring: Persistent key-value storage för prenumeranter
Betalning: Swish Handel (integreras vid lansering)
E-post: Mailgun (planeras)
---
Filer
Fil	Beskrivning	Intäkt
`index.html`	Landningssida	—
`app.html`	Manuell jämförelseapp	79 kr/st
`ai-app.html`	AI-driven version med PDF-uppladdning	79 kr/st
`bevaka.html`	Prenumerationstjänst för räntebevakning	29 kr/mån
`admin.html`	Admin-panel för räntuppdateringar	—
`privacy.html`	Integritetspolicy (GDPR)	—
---
Intäktsmodell
Produkt	Pris	100 kunder/mån
Engångsanalys	79 kr	7 900 kr
Räntebevakning	29 kr/mån	2 900 kr/mån återkommande
Totalt år 1		~42 000 kr
---
Kom igång lokalt
```bash
git clone https://github.com/Fraxinus87/bolanejakten.git
cd bolanejakten
open index.html
```
---
Roadmap
[x] Manuell jämförelseapp
[x] Bankjämförelse mot 6 storbanker
[x] Förhandlingsskript
[x] Live på bolanejakten.se
[x] AI-driven version med PDF-uppladdning
[x] AI-genererat förhandlingsbrev
[x] Räntebevakningstjänst med prenumeration
[ ] Swish Handel-integration
[ ] Mailgun e-postutskick
[ ] BankID-integration
[ ] Affiliate-avtal med SBAB/Länsförsäkringar
[ ] SEO-blogg för organisk trafik
---
Kontakt
📧 hej@bolanejakten.se  
🌐 bolanejakten.se
---
Bolånejakten är ett informationsverktyg — inte finansiell rådgivning.
