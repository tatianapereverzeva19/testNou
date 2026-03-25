# Teme pentru acasă — Modulul 10

---

## Lecția 0 - Build Your Business Intelligence Command Center

**Tema pentru acasă:** Identifică 5 întrebări critice la care nu poți răspunde instant despre un business, folosind Claude Code ca instrument de brainstorming.

---

**1. Alege un business și deschide Claude Code**

1. Deschide Claude Code în terminal (`claude --dangerously-skip-permissions`)
2. Rulează skill-ul de brainstorming: `/brainstorming`
3. Alege un business — al tău, locul unde lucrezi sau unul pe care vrei să-l lansezi

---

**2. Generează lista de întrebări cu Claude Code**

1. Spune-i lui Claude Code: *„Ajută-mă să identific 5 întrebări despre business-ul meu la care nu pot răspunde instant fără să caut prin mai multe tool-uri."*
2. Exemple de întrebări relevante:
   - Cât revenue am făcut săptămâna asta față de săptămâna trecută?
   - Care canal de marketing aduce clienți care chiar cumpără?
   - Câți clienți am pierdut în ultimele 3 luni și de ce?
   - Care este produsul cel mai profitabil (nu cel mai vândut)?
   - Dacă trendul continuă, unde voi fi peste 3 luni?
3. Salvează lista generată într-un fișier pe calculator — **nu de mână**, cu Claude Code

---

**3. Verifică calitatea întrebărilor**

Înainte să treci mai departe, asigură-te că:
- Ai exact 5 întrebări specifice și măsurabile
- Cel puțin 3 dintre ele necesită date din surse diferite (ex: Analytics + CRM + Stripe)
- Fiecare poate fi răspuns cu un număr, un grafic sau un trend

---

**Cum știi că ai reușit?**
- [ ] Claude Code deschis și skill-ul de brainstorming rulat
- [ ] 5 întrebări generate și salvate într-un fișier
- [ ] Cel puțin 3 întrebări necesită date din surse diferite
- [ ] Fiecare întrebare poate fi răspunsă cu un număr sau un trend



---

## Lecția 1 - KPIs, Metrici și Vanity Metrics — Ghidul Tău Complet

**Tema pentru acasă:** Analizează datele din serverul BI cu agenți paraleli, alege top 5 KPI-uri pentru dashboard-ul tău și identifică un vanity metric din domeniul tău.

---

**1. Pornește serverul BI și rulează analiza cu agenți paraleli**

1. Deschide Claude Code și rulează: `/bi-data-server` → **Start Server**
2. Odată ce serverul rulează, deschide o a doua instanță Claude Code
3. Spune-i: *„Uită-te pe serverul de la adresa [adresa serverului]. Cheia de API este [cheia din fișierul readme]. Uită-te exact ce tip de date există pe serverul ăsta și fă-ți o imagine mentală a datelor."*
4. Apoi rulează: `/brainstorming` cu promptul: *„Fă o analiză complexă a acestor date folosind 5–10 agenți paraleli care se verifică unul pe celălalt și determină 10 KPI-uri: 5 leading indicators și 5 lagging indicators."*

---

**2. Selectează top 5 KPI-uri**

1. Din lista generată de agenți, alege 5 KPI-uri: cel puțin 2 leading și cel puțin 2 lagging
2. Pentru fiecare KPI ales, scrie o propoziție completă după modelul:
   - *„[Numele KPI] este important pentru că dacă îl ignori, riscul este [descrierea riscului concret]."*
3. Cere-i lui Claude Code să salveze KPI-urile în `docs/kpi-report.md` cu definiția și target-ul fiecăruia

---

**3. Identifică un vanity metric și înlocuiește-l**

1. Gândește-te la un indicator pe care îl urmărești acum sau pe care l-ai urmărit în trecut (ex: numărul de followeri, vizualizări totale, descărcări cumulative)
2. Testează-l cu cele 3 criterii:
   - Informează o decizie concretă?
   - Poate fi reprodus consistent?
   - Reflectă fidel realitatea?
3. Dacă nu trece testul, este vanity — identifică KPI-ul acționabil care ar trebui să îl înlocuiască

---

**Cum știi că ai reușit?**
- [ ] Serverul BI pornit și analiza cu agenți paraleli executată
- [ ] 5 KPI-uri selectate (minim 2 leading + 2 lagging)
- [ ] O propoziție despre importanță și risc scrisă pentru fiecare KPI
- [ ] Fișierul `docs/kpi-report.md` salvat cu definiție și target per KPI
- [ ] Un vanity metric identificat și KPI-ul acționabil propus în locul lui



---

## Lecția 2 - Construiește Prima Ta Aplicație Web cu Next.js

**Tema pentru acasă:** Creează un proiect Next.js folosind Claude Code, pornește serverul și verifică în browser că aplicația rulează.

---

**1. Creează proiectul Next.js cu Claude Code**

1. Deschide Claude Code (`claude --dangerously-skip-permissions`)
2. Scrie: *„Vreau să creez o aplicație de Next.js în folderul BI-Dashboard și să scrii un CLAUDE.md pentru el. În CLAUDE.md trebuie spus cum se pornește și se oprește serverul și cum trebuie să lucrăm cu proiectul. El va conține instrucțiuni că trebuie să se updateze când se creează pattern-uri noi în proiect."*
3. Aprobă comenzile pe care Claude Code le propune pentru instalare

---

**2. Pornește serverul și verifică în browser**

1. Spune-i lui Claude Code: *„Pornește serverul"*
2. Claude Code îți va da o adresă de genul `localhost:3000` (sau alt port)
3. Ține apăsat `Ctrl` și dă click pe adresă — se va deschide în browser
4. Verifică că există o pagină (chiar dacă este goală sau cu conținut default Next.js)

---

**3. Explorează structura proiectului**

1. Deschide folderul proiectului în VS Code
2. Identifică și notează unde se află:
   - Folderul `app/` — paginile aplicației
   - Folderul `app/api/` — rutele de backend
   - Fișierul `CLAUDE.md` — instrucțiunile pentru Claude Code
   - Fișierul `.env` — cheile secrete (dacă există)
3. Deschide fișierul `app/page.tsx` sau `app/page.js` și identifică ce text apare în browser

---

**4. Oprește serverul**

1. Spune-i lui Claude Code: *„Oprește serverul"*
2. Verifică că serverul s-a oprit (pagina din browser nu mai funcționează)

---

**5. Opțional — Configurează cheia Anthropic**

1. Cere-i lui Claude Code să creeze fișierul `.env` cu `ANTHROPIC_API_KEY=cheia_ta`
2. Verifică că fișierul `.env` este listat în `.gitignore`

---

**Cum știi că ai reușit?**
- [ ] Proiect Next.js creat în folderul `BI-Dashboard`
- [ ] Fișierul `CLAUDE.md` creat cu instrucțiuni de rulare
- [ ] Serverul pornit și pagina vizibilă în browser la adresa dată de Claude Code
- [ ] Structura proiectului explorată și folderele-cheie identificate
- [ ] Textul din `app/page.tsx` identificat și corelat cu ce apare în browser
- [ ] Serverul oprit cu Claude Code
- [ ] (Opțional) Fișierul `.env` configurat cu cheia Anthropic



---

## Lecția 3 - Construiește-ți Echipa de Agenți pentru BI Dashboard

**Tema pentru acasă:** Creează o echipă de 4 agenți specializați (PM, Front-end Dev, Back-end Dev, Data Analyst) și execută un task DAG simplu pentru a testa că echipa funcționează.

---

**1. Creează echipa de 4 agenți (sau folosește echipa din lecție)**

Dacă ai urmărit demo-ul, ai deja agenții creați. Dacă nu, găsești agenții gata făcuți în resursele de sub video.

Echipa ta trebuie să conțină:
- **Project Manager (PM)** — planifică, coordonează și verifică la final
- **Front-end Dev** — construiește interfața vizuală în Next.js
- **Back-end Dev** — creează rutele de API și conexiunile cu baza de date
- **Data Analyst** — curăță datele și creează analize

---

**2. Configurează design language-ul (pentru Front-end Dev)**

1. Alege un design language din cele puse la dispoziție (ex: Coral Sketch sau altul care îți place)
2. Spune-i lui Claude Code: *„Pune design language-ul [numele ales] în skill-ul de front-end unde este design language."*

---

**3. Creează și rulează skill-ul `start`**

1. Dacă nu ai skill-ul `start` creat deja, cere-i lui Claude Code să îl creeze (este skill-ul care pornește întreaga echipă)
2. Deschide o nouă sesiune Claude Code în folderul `BI-Dashboard`
3. Rulează: `/start`
4. Descrie task-ul: *„Vreau un feature mic care creează o rută de API health. Frontend-ul pe pagina principală arată statusul serverului."*

---

**4. Urmărește echipa și verifică în browser**

1. Urmărește cum fiecare agent primește și execută task-ul său
2. Când echipa termină, deschide browserul la adresa dată de Claude Code
3. Verifică că pagina afișează statusul serverului (online/offline)

---

**5. Explică fluxul**

Scrie sau spune cu voce tare (sau pune în comentarii):
- Care agent a făcut ce?
- În ce ordine au lucrat?
- Care task a depins de celălalt (task DAG)?

---

**Cum știi că ai reușit?**
- [ ] Echipă de 4 agenți disponibilă (creată sau descărcată din resurse)
- [ ] Design language configurat în skill-ul de front-end
- [ ] Skill-ul `start` rulat cu un feature simplu de API health
- [ ] Pagina din browser afișează statusul serverului
- [ ] Fluxul DAG explicat: care agent ce a făcut și în ce ordine
- [ ] (Bonus) Screenshot sau descriere postată în comentarii



---

## Lecția 4 - Cum să Centralizezi Datele din 5 Surse Diferite

**Tema pentru acasă:** Pornește BI Dashboard-ul, verifică că baza de date a fost populată corect și testează rutele de API disponibile.

---

**1. Pornește BI Dashboard-ul și serverul de date**

1. Deschide Claude Code în folderul `BI-Dashboard` (`claude --dangerously-skip-permissions`)
2. Rulează: `/start` sau `/bi-data-server` → **Start Server**
3. Confirmă că serverul rulează și că baza de date a fost creată

---

**2. Verifică câte rânduri s-au creat**

1. Spune-i lui Claude Code: *„Câte rânduri s-au creat în baza de date? Arată-mi câte rânduri are fiecare tabelă."*
2. Verifică că ai date pentru toate cele 5 surse (Shopify, GA4, Meta Ads, MailChimp, Zendesk)
3. Verifică că ai date pentru 12 luni

---

**3. Testează rutele de API**

Testează fiecare rută de API spunând lui Claude Code să deschidă adresele:

1. **API Revenue** — *„Deschide ruta /api/revenue și arată-mi primele 5 rânduri de date."*
2. **API Customers** — *„Deschide ruta /api/customers. Câte segmente de clienți există?"*
3. **API Marketing** (opțional) — verifică datele de marketing
4. **API Products** (opțional) — verifică datele despre produse
5. **API Support** (opțional) — verifică datele din Zendesk
6. **API KPIs** — *„Deschide ruta /api/kpis și verifică că avem date pentru leading și lagging indicators."*

---

**4. Verifică calitatea datelor**

1. Spune-i lui Claude Code: *„Verifică dacă există valori lipsă sau inconsistențe în datele din baza de date."*
2. Dacă găsește probleme, întreabă: *„Cum putem curăța aceste date?"*

---

**5. Opțional — Testează ETL incremental**

1. Spune-i lui Claude Code: *„Rulează un update incremental — actualizează doar ultimele 2 luni de date."*
2. Verifică că durează mai puțin decât un full update

---

**Cum știi că ai reușit?**
- [ ] Serverul BI pornit și baza de date creată
- [ ] Numărul de rânduri din fiecare tabelă verificat
- [ ] Ruta `/api/revenue` testată și datele vizualizate
- [ ] Ruta `/api/customers` testată — segmentele de clienți identificate
- [ ] Ruta `/api/kpis` testată — leading și lagging indicators verificate
- [ ] (Opțional) Restul rutelor de API testate
- [ ] (Opțional) ETL incremental testat și comparat ca viteză cu full ETL



---

## Lecția 5 - Cum să Creezi Dashboard-uri Eficiente cu KPI Carduri

**Tema pentru acasă:** Adaugă 5 carduri KPI pe pagina principală a BI Dashboard-ului, cu indicatori de culoare, săgeți de trend și comparație cu luna precedentă.

---

**1. Pornește echipa de agenți și descrie feature-ul**

1. Deschide Claude Code în folderul `BI-Dashboard` (`claude --dangerously-skip-permissions`)
2. Rulează `/start` ca să pornești echipa de agenți
3. Descrie ce vrei să construiești:
   *„Vreau să creez 5 carduri KPI pe pagina principală. Fiecare card trebuie să aibă: titlu, valoare principală mare, săgeată de trend cu procentaj față de luna trecută, valoarea lunii precedente și o culoare de status (verde = bine, galben = atenție, roșu = problemă critică). Cardurile sunt: Revenue, Clienți noi, Conversion Rate, AOV (Average Order Value) și Support Tickets."*

---

**2. Participă la sesiunea de brainstorming**

1. Răspunde la întrebările echipei de agenți despre design și date
2. Când îți arată mock-up-uri vizuale în browser, alege varianta care îți place
3. Asigură-te că ai specificat:
   - **Lagging indicators** (Revenue, Clienți noi, AOV) să afișeze ultima lună completă
   - **Leading indicators** (Conversion Rate, Support Tickets) să afișeze luna curentă
   - Culorile să fie aliniate cu design language-ul proiectului

---

**3. Verifică cardurile în browser**

1. Deschide `localhost:3000` după ce echipa termină
2. Verifică fiecare card:
   - Titlul este corect afișat?
   - Valoarea principală este mare și vizibilă?
   - Săgeata arată direcția corectă (↑ sau ↓)?
   - Culoarea corespunde statusului (verde / galben / roșu)?
3. Dacă ceva nu arată bine, fă un screenshot și trimite-l înapoi în Claude Code cu o descriere a problemei

---

**4. Examinează cele 5 carduri și extrage insight-uri**

1. Deschide dashboard-ul și răspunde la aceste întrebări:
   - Care card este verde? Ce înseamnă asta pentru business?
   - Care card este roșu sau galben? Ce trebuie să faci?
   - Revenue a crescut sau a scăzut față de luna trecută?
   - Support Tickets cresc? Atenție — mai puțin înseamnă mai bine!
2. Scrie **3 propoziții** care rezumă starea business-ului bazat pe cele 5 carduri

---

**Cum știi că ai reușit?**
- [ ] 5 carduri KPI afișate pe pagina principală
- [ ] Fiecare card are: titlu, valoare, trend (săgeată + %), valoare precedentă și culoare de status
- [ ] Lagging indicators afișează ultima lună completă, leading indicators luna curentă
- [ ] Culorile verde / galben / roșu funcționează corect
- [ ] 3 propoziții cu insight-uri din carduri scrise și postate în comentarii
- [ ] (Bonus) Screenshot cu dashboard-ul tău postat în comentarii



---

## Lecția 6 - Vizualizarea Trendurilor cu Grafice Interactive

**Tema pentru acasă:** Adaugă 3 grafice interactive sub cardurile KPI: Revenue Trend cu forecast, Traffic by Channel și Conversion Funnel.

---

**1. Pornește echipa și descrie cele 3 grafice**

1. Rulează `/start` în Claude Code
2. Descrie feature-ul:
   *„Vreau să adaug 3 grafice interactive sub cardurile KPI. 1. Revenue Trend — area chart pe 12 luni cu linie punctată de forecast pe 3 luni (metodă: medie mobilă pe ultimele 3 luni). 2. Traffic by Channel — bar chart cu bare suprapuse, câte o culoare per canal din GA4. 3. Conversion Funnel — de la Impresii la Cumpărare, cu 6 pași. Toate graficele trebuie să folosească recharts și să preia datele din API-urile existente."*

---

**2. Ia decizii în sesiunea de brainstorming**

Echipa de agenți îți va pune întrebări. Răspunsuri recomandate:
- **Forecast:** medie mobilă pe ultimele 3 luni (mai conservator, mai realist)
- **Conversion Funnel:** bare orizontale sau trapezoid — alege ce preferi vizual
- **Date:** din API-urile existente, nu din endpoint-uri noi

---

**3. Verifică graficele în browser și raportează problemele**

1. Deschide `localhost:3000` și verifică fiecare grafic
2. Testează interactivitatea — treci cu mouse-ul peste grafice și verifică tooltipurile
3. Dacă găsești probleme (date incorecte, luni greșit sortate, valori ciudate), fă screenshot și trimite în Claude Code cu descrierea problemei

---

**4. Analizează graficele și extrage insight-uri**

Deschide dashboard-ul și răspunde:
- **Revenue Trend**: Care a fost cea mai bună lună? Cea mai slabă? Forecast-ul este ascendent sau descendent?
- **Traffic by Channel**: Care canal domină? Care a crescut cel mai mult în ultimele 3 luni?
- **Conversion Funnel**: Unde este cel mai mare drop-off? Care este rata finală de conversie?

Scrie un **mini-raport de 3 propoziții** cu ce ai aflat din cele 3 grafice.

---

**Cum știi că ai reușit?**
- [ ] Revenue Trend area chart cu linie punctată de forecast afișat
- [ ] Traffic by Channel stacked bar chart cu culori diferite per canal afișat
- [ ] Conversion Funnel cu minim 5 pași afișat
- [ ] Tooltipuri interactive funcționale la hover
- [ ] Graficele preiau date reale din API-uri (nu date hardcodate)
- [ ] Mini-raport de 3 propoziții cu insight-uri din grafice postat în comentarii
- [ ] (Bonus) Screenshot cu dashboard-ul complet (carduri + grafice) postat



---

## Lecția 7 - Organizarea Dashboard-ului în Tab-uri Dedicate

**Tema pentru acasă:** Transformă dashboard-ul dintr-o singură pagină în 6 tab-uri dedicate cu navigație laterală collapsible: Overview, Marketing, Support, Sales, Expenses și GapFinder.

---

**1. Pornește echipa și descrie cele 6 tab-uri**

1. Rulează `/start` în Claude Code
2. Descrie feature-ul complet:
   *„Vreau să creez 6 pagini separate cu o bară de navigare laterală: /marketing, /support, /sales, /expenses, /gapfinder și pagina principală ca Overview. Bara de navigare să fie collapsible. Fiecare pagină să aibă KPI carduri specifice + grafice relevante."*
3. Specifică ce date vrei pe fiecare pagină:
   - **Marketing**: trafic pe sursă, cost pe achiziție trend, campanii MailChimp
   - **Support**: tichete pe tag, volum tichete trend, status tichete
   - **Sales**: revenue pe categorie, top 10 produse, AOV trend
   - **Expenses**: cheltuieli pe categorie, distribuție cheltuieli (pie chart), trend cheltuieli vs revenue
   - **GapFinder**: tabel comparativ Shopify vs GA4, gap-uri detectate > 10%

---

**2. Alege designul navigației**

Când echipa îți arată opțiuni vizuale pentru sidebar:
- Alege stilul de iconițe care se potrivește cu design language-ul proiectului
- Alege layout-ul paginilor (recomandat: KPI cards + grafice adaptate per pagină)

---

**3. Verifică fiecare tab în browser**

După ce echipa termină, verifică pe rând fiecare tab:
1. **Marketing**: Graficele se încarcă? ROAS pe canal afișat corect?
2. **Support**: Lunile sunt sortate cronologic (nu alfabetic)?
3. **Sales**: Revenue pe categorie corect? Repeat vs. new customers din luna curentă completă?
4. **Expenses**: Graficul trend cheltuieli vs revenue are scalele corecte?
5. **GapFinder**: Gap-urile > 10% sunt vizibile? Lunile sub prag sunt excluse cu un mesaj?
6. **Sidebar collapsible**: Funcționează butonul de collapse? Animația este fluidă?

Raportează orice problemă găsită cu screenshot + descriere.

---

**4. Răspunde la întrebările de business din fiecare tab**

- **Marketing**: Ce canal domină? CPA meta crește sau scade? Ce campanie MailChimp a mers cel mai bine?
- **Support**: Ce tag domină? Volumul crește sau scade?
- **Sales**: Ce categorie generează cel mai mult revenue? Care e produsul #1?
- **Expenses**: Care categorie de cheltuieli domină? Marja crește sau scade?
- **GapFinder**: Care lună are gap-ul cel mai mare față de 10%?

---

**Cum știi că ai reușit?**
- [ ] 6 tab-uri cu routing correct: `/`, `/marketing`, `/support`, `/sales`, `/expenses`, `/gapfinder`
- [ ] Bara de navigare vizibilă pe toate paginile
- [ ] Sidebar collapsible funcțional
- [ ] Fiecare pagină afișează date specifice (nu aceleași date peste tot)
- [ ] Lunile sortate cronologic pe toate graficele de trend
- [ ] Răspunsuri la întrebările de business din fiecare tab postate în comentarii
- [ ] (Bonus) Screenshot cu navigația și minim 3 tab-uri vizibile



---

## Lecția 8 - Integrează AI în Dashboard-ul Tău — Insight-uri Automate

**Tema pentru acasă:** Adaugă AI Insights pe dashboard folosind Claude API sau Claude Code local, și generează primul tău raport de analiză automată a business-ului.

---

**1. Alege modul de generare a insight-urilor**

Ai două opțiuni:
- **Modul 1 — Claude API** (recomandat): necesită cheie API de pe `platform.anthropic.com` și costuri ~5 cenți per analiză
- **Modul 2 — Claude Code local** (gratuit): folosește abonamentul Claude Code existent, dar insight-urile nu se regenerează automat

Dacă alegi **Modul 1**, creează-ți cont pe `platform.anthropic.com`, pune minim $5 pe cont și generează o cheie API nouă.

---

**2. Pornește echipa și descrie feature-ul**

1. Rulează `/start` în Claude Code
2. Descrie ce vrei:
   *„Vreau să adaug AI Insights pe dashboard. Vreau un API route /api/insights care citește datele din SQLite, le trimite la Claude API (cheia mea este [cheia ta]) și returnează un JSON cu insight-uri pe secțiuni: Sales, Marketing, Support, Expenses, Products și Gap Analysis. Pe fiecare pagină a dashboard-ului să apară un card de AI Insights sub KPI carduri. Insight-urile să fie cached 5 minute în memoria serverului ca să optimizăm costurile. Adaugă și o pagină dedicată /ai-insights cu un raport complet. Modelul să fie claude-haiku pentru costuri minime."*
3. Specifică că vrei **sistem prompt separat** (pentru prompt caching) și **user prompt cu datele** (se schimbă per request)

---

**3. Ia decizii în brainstorming**

Când echipa pune întrebări:
- **Layout insight card**: card compact sub KPI, collapsible
- **Pagina AI Insights**: raport linear cu secțiuni (Sales, Marketing, Support etc.)
- **Animație loading**: spinner sau skeleton loader cât se generează
- **Buton refresh manual**: da, adaugă-l pe lângă cache-ul automat de 5 minute

---

**4. Verifică și analizează insight-urile generate**

1. Deschide dashboard-ul și așteaptă 3-5 secunde să se încarce insight-urile
2. Citește fiecare insight și verifică că are structura: **Ce s-a întâmplat → De ce contează → Ce să faci**
3. Mergi pe pagina `/ai-insights` și citește raportul complet
4. Verifică **Top 3 Acțiuni Recomandate** — sunt relevante pentru business?

---

**5. Exercițiu de gândire critică**

1. Apasă butonul **Refresh** și generează un set nou de insight-uri
2. Alege **un insight cu care nu ești de acord** și explică de ce în comentarii
3. Compară insight-urile generate cu ce știai deja despre datele din dashboard — AI-ul a găsit ceva nou?

---

**Cum știi că ai reușit?**
- [ ] Ruta `/api/insights` creată și funcțională
- [ ] Card AI Insights afișat pe cel puțin pagina Overview
- [ ] Insight-urile au structura: observație + importanță + acțiune recomandată
- [ ] Pagina `/ai-insights` cu raport complet și Top 3 Acțiuni afișată
- [ ] Butonul de Refresh funcțional
- [ ] Cache de 5 minute implementat (nu face request nou la fiecare refresh de pagină)
- [ ] Un insight contestat cu argumentare postată în comentarii
- [ ] (Bonus) Insight-uri generate cu ambele moduri (API + Claude Code local) comparate



---

## Lecția 9 - Finalizarea Business Command Center — Filtre și Raportare

**Tema pentru acasă:** Adaugă un filtru de perioadă (7D / 30D / 90D / 12L) care actualizează tot dashboard-ul și un buton de export PDF cu raportul complet al business-ului.

---

**1. Pornește echipa și descrie cele 2 feature-uri finale**

1. Rulează `/start` în Claude Code
2. Descrie ambele feature-uri:
   *„Vreau să implementez două feature-uri finale. 1. Un filtru de perioadă în top bar cu 4 butoane: 7Z (7 zile), 30Z (30 zile), 90Z (90 zile) și 12L (12 luni). Filtrul trebuie să persiste prin URL search parameters când navighez între tab-uri. Toate graficele și cardurile KPI se actualizează la schimbarea filtrului. 2. Un buton de Export PDF în colțul din dreapta sus care generează un raport complet stilizat cu AI Insights la început, toate KPI-urile, trend-urile principale și perioada selectată."*
3. Menționează că datele zilnice (pentru 7Z și 30Z) pot necesita tabele noi în baza de date

---

**2. Ia decizii în brainstorming**

Când echipa pune întrebări:
- **Persistența filtrului**: URL Search Parameters (permite share-uirea link-ului cu filtrul activ)
- **PDF layout**: raport linear cu toate secțiunile (nu screenshot, ci document structurat)
- **Top bar**: sticky cu efect frosted glass, conținut trece pe sub el la scroll
- **Fonturile PDF**: folosește fișiere `.ttf` statice din folderul `public/fonts/`

---

**3. Testează filtrul de perioadă**

1. Deschide dashboard-ul și apasă pe fiecare buton de filtru (7Z → 30Z → 90Z → 12L)
2. Verifică că:
   - Cardurile KPI se actualizează la schimbarea filtrului
   - Graficele afișează datele pentru perioada selectată
   - URL-ul se schimbă (ex: `?range=7d`)
   - Filtrul **rămâne activ** când navighezi între tab-uri
3. Raportează orice problemă găsită (date invalide, „Invalid Date", grafice goale)

---

**4. Testează exportul PDF**

1. Selectează un filtru (ex: 30Z)
2. Apasă butonul **Export PDF**
3. Verifică că PDF-ul conține:
   - AI Insights / Executive Summary la început
   - KPI-urile principale
   - Informații din toate tab-urile (Marketing, Support, Sales, Expenses)
   - Perioada selectată (30 de zile) menționată în raport
4. Dacă apare o eroare, copiază mesajul de eroare și trimite-l în Claude Code

---

**5. Demo Walkthrough — Prezintă dashboard-ul complet**

Simulează o prezentare a dashboard-ului ca și cum l-ai arăta unui investitor sau manager:
1. Cronometrează-te — încearcă să termini în **2-3 minute**
2. Parcurge pe rând: Overview → Marketing → Support → Sales → Expenses → GapFinder → AI Insights
3. Schimbă filtrul la 90Z și observă cum se actualizează datele
4. Generează raportul PDF și verifică că este prezentabil

---

**6. Bonus — Personalizează dashboard-ul**

1. Cere echipei să schimbe titlul dashboard-ului cu numele business-ului tău
2. Ajustează pragurile de culoare (verde/galben/roșu) pe cardurile KPI la valori relevante pentru tine
3. Sau du mai departe: adaptează tot dashboard-ul pe datele reale ale business-ului tău

---

**Cum știi că ai reușit?**
- [ ] Filtru cu 4 butoane (7Z / 30Z / 90Z / 12L) afișat în top bar pe toate paginile
- [ ] Filtrul persistă prin URL când navighezi între tab-uri
- [ ] Toate graficele și cardurile KPI se actualizează la schimbarea filtrului
- [ ] Export PDF funcțional cu conținut structurat (nu screenshot)
- [ ] PDF-ul respectă filtrul activ (datele din raport corespund perioadei selectate)
- [ ] Demo Walkthrough complet în 2-3 minute realizat
- [ ] (Bonus) Titlul și pragurile KPI personalizate pentru business-ul tău
- [ ] Screenshot sau PDF exportat postat în comentarii
