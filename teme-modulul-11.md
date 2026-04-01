# Teme pentru acasă — Modulul 11

---

## Lecția 0 - Bine ai venit în Modulul 11: Construiește soluții pentru industria ta

Această lecție este o introducere în structura modulului. Nu există o temă specifică, dar ai un pas important de făcut:

**Acțiune:**
1. Identifică în ce categorie te încadrezi:
   - Antreprenor
   - Freelancer / Consultant
   - Solopreneur
   - Influencer / Creator de conținut
   - Tech / Developer
2. Decide ce secțiune specifică vei parcurge în modulul 11 (în afara secțiunii transversale)
3. Scrie în 2-3 propoziții ce problemă concretă din industria ta vrei să rezolvi cu AI până la finalul modulului

---

## Lecția 0A - GitHub pentru non-tehnici: Resurse gratuite și automatizări

**Tema pentru acasă:** Creează-ți cont pe GitHub, găsește un proiect relevant pentru domeniul tău și clonează-l cu Claude Code.

---

**1. Creează-ți cont pe GitHub**

1. Intră pe `github.com` și apasă **Sign Up**
2. Poți să te înregistrezi cu Google, Apple sau manual cu email și parolă
3. Completează procesul de înregistrare

---

**2. Găsește un proiect relevant pentru tine**

1. Caută pe Google sau direct în bara de search din GitHub — **în engleză** pentru mai multe rezultate
2. Adaugă cuvinte cheie din domeniul tău: `email automation`, `invoice templates`, `social media scheduler`, `landing page builder` etc.
3. Filtrează după stele: în bara de căutare GitHub adaugă `stars:>100` sau `stars:>1000`
4. Regula de bază: **peste 1000 de stele + README clar = proiect de încredere**

---

**3. Evaluează proiectul găsit**

Înainte să-l clonezi, verifică:
- Câte stele are?
- Când a fost ultima actualizare (recent = activ)?
- Are un README clar cu instrucțiuni?

---

**4. Clonează proiectul cu Claude Code**

1. Copiază link-ul proiectului din bara de adresă a browserului
2. Deschide Claude Code într-un folder gol
3. Scrie: *„Clonează-mi repo-ul ăsta de GitHub și spune-mi ce se află în el. Atenție, eu sunt non-tehnic, explică-mi cu un limbaj de clasa a 9-a."* și lipești link-ul
4. Prima dată când rulezi comanda, Claude Code te va ajuta să te loghezi la GitHub

---

**5. Explorează proiectul clonat**

1. Citește ce ți-a explicat Claude Code despre proiect
2. Dacă nu ai înțeles ceva, pune-i o întrebare suplimentară
3. Opțional: dacă vrei să urci unul dintre proiectele tale pe GitHub, spune-i lui Claude Code: *„Vreau să urc folderul curent pe GitHub cu numele [numele proiectului]"*

---

**Cum știi că ai reușit?**
- [ ] Cont de GitHub creat și activ
- [ ] Un proiect cu cel puțin 100 de stele găsit în domeniul tău
- [ ] README-ul citit și înțeles
- [ ] Proiectul clonat cu Claude Code pe calculatorul tău
- [ ] Claude Code a explicat ce face proiectul în limbaj accesibil
- [ ] (Bonus) Unul dintre proiectele tale urcat pe GitHub

---

## Lecția 0B - Prezentări profesionale în câteva minute cu AI

**Tema pentru acasă:** Generează o prezentare profesională completă folosind Cloud Code și adaptează skill-ul de prezentări pentru nevoile tale.

---

**1. Deschide proiectul de prezentări în Cloud Code**

1. Descarcă proiectul de prezentări furnizat la lecție
2. Deschide-l în Cloud Code
3. Rulează comanda `/plan slides` și descrie prezentarea pe care vrei să o creezi

---

**2. Definește cele 3 coordonate ale prezentării tale**

Spune-i lui Cloud Code:
- **Ce faci** — descrie afacerea sau proiectul tău în 1-2 propoziții
- **Cine-i audiența** — cine va vedea prezentarea (investitori, clienți, echipă, etc.)
- **Ce vrei să obții** — ce acțiune vrei să ia audiența după prezentare

Opțional: dacă ai documente despre afacerea ta (oferte, rapoarte, descrieri), pune-le în folderul proiectului cu drag-and-drop înainte să pornești.

---

**3. Generează prezentarea**

1. Răspunde la toate întrebările clarificatoare pe care le pune Cloud Code
2. Alege stilul vizual preferat (ex: minimalist, corporate bright, etc.)
3. Lasă Cloud Code să genereze imaginile și prezentarea completă în format HTML
4. Deschide fișierul `index.html` generat și verifică rezultatul

---

**4. Iterează și îmbunătățește**

1. Alege un slide care nu îți place sau care poate fi îmbunătățit
2. Cere lui Cloud Code să îl modifice (ex: *„Simplifică slide-ul 3, e prea încărcat"* sau *„Adaugă mai multe cifre pe slide-ul 2"*)
3. Verifică rezultatul după modificare

---

**5. Adaptează skill-ul pentru nevoile tale**

1. Identifică ce stil de slide îți place cel mai mult din prezentarea generată
2. Actualizează skill-ul de prezentări în Cloud Code ca să folosească implicit acel stil
3. Testează cu o a doua prezentare mai scurtă (5-7 slide-uri) ca să confirmi că skill-ul funcționează cum vrei

---

**Livrabil final**

Postează în grupul de Telegram sau în comentariile lecției:
- Un screenshot sau link cu prezentarea ta generată
- Ce tip de prezentare ai ales și pentru ce audiență

---

**Cum știi că ai reușit?**
- [ ] Prezentarea generată are cel puțin 10 slide-uri
- [ ] Stilul vizual se potrivește cu audiența aleasă
- [ ] Ai făcut cel puțin o iterație de îmbunătățire pe un slide
- [ ] Skill-ul a fost actualizat să genereze în stilul preferat de tine
- [ ] Fișierul HTML se deschide și arată profesional în browser

---

## Lecția 0C - Automatizări WhatsApp cu Twilio

**Tema pentru acasă:** Configurează un bot WhatsApp cu Twilio și Claude Code care trimite automat cel puțin un tip de mesaj relevant pentru afacerea ta.

---

**1. Creează-ți cont Twilio și activează sandbox-ul WhatsApp**

1. Intră pe `twilio.com` și creează un cont gratuit
2. În dashboard, caută secțiunea **Messaging → Try it out → Send a WhatsApp message**
3. Urmează instrucțiunile pentru activarea sandbox-ului: trimite codul de activare pe WhatsApp la numărul indicat de Twilio
4. Salvează într-un fișier `.env` datele tale: `TWILIO_ACCOUNT_SID`, `TWILIO_AUTH_TOKEN`, `TWILIO_WHATSAPP_NUMBER`

---

**2. Planifică automatizarea ta**

Înainte să construiești, decide ce tip de mesaj vrei să automatizezi. Exemple:
- Memento de programare (trimis cu 24h înainte)
- Mesaj de bun venit pentru clienți noi
- Follow-up după o achiziție
- Răspuns automat la întrebări frecvente

Scrie în 2-3 propoziții: **ce mesaj trimiți, cui și când se declanșează**.

---

**3. Construiește automatizarea cu Claude Code**

1. Deschide Claude Code cu fișierul `.env` configurat
2. Descrie ce vrei să construiești:
   *„Vreau să construiesc o automatizare WhatsApp cu Twilio care [descrie cazul tău]. Folosește credențialele din fișierul .env. Vreau să pot testa trimiterea unui mesaj de test direct din terminal."*
3. Aprobă pașii propuși de Claude Code și instalează dependențele necesare

---

**4. Testează mesajul de test**

1. Rulează scriptul de test generat de Claude Code
2. Verifică pe telefonul tău că ai primit mesajul WhatsApp
3. Dacă nu a ajuns, cere-i lui Claude Code să diagnosticheze problema: *„Mesajul nu a ajuns. Uite eroarea: [copiază eroarea]"*

---

**5. Personalizează mesajul**

1. Modifică textul mesajului să fie relevant pentru clienții tăi
2. Dacă vrei mesaje dinamice (cu numele clientului, data programării etc.), spune-i lui Claude Code să adauge parametri personalizabili
3. Testează din nou cu mesajul personalizat

---

**Cum știi că ai reușit?**
- [ ] Cont Twilio creat și sandbox WhatsApp activat
- [ ] Fișierul `.env` configurat cu credențialele Twilio
- [ ] Automatizarea construită cu Claude Code
- [ ] Mesaj de test primit pe WhatsApp
- [ ] Mesajul este personalizat pentru afacerea ta (nu textul default)
- [ ] (Bonus) Automatizarea se declanșează la un trigger real (programare, formular, etc.)
- [ ] Screenshot cu mesajul primit postat în comentarii

---

## Lecția 1A - Cum să validezi ideea ta de business înainte de a investi

**(Secțiunea Antreprenori)**

**Tema pentru acasă:** Rulează pipeline-ul complet de validare pentru o idee de business a ta — sondaj, analiză competitivă, estimarea pieței, pagină de test și scor final.

---

**1. Alege ideea de validat și pregătește Claude Code**

1. Deschide Claude Code cu skill-ul de brainstorming: `/brainstorming`
2. Descrie ideea ta în 2-3 propoziții: ce este, pentru cine și ce problemă rezolvă
3. Spune-i lui Claude Code că vrei să rulezi un pipeline de validare în 5 pași

---

**2. Pasul 1 — Analiza competitivă (3-4 agenți paraleli)**

1. Cere-i lui Claude Code să pornească 3-4 agenți paraleli care caută pe internet competitorii din nișa ta
2. Agenții să identifice: cine sunt primii 5-7 competitori, ce oferă, la ce preț și unde sunt golurile
3. Salvează documentul de analiză competitivă în format Markdown

---

**3. Pasul 2 — Estimarea dimensiunii pieței (TAM, SAM, SOM)**

1. Pornește 3-5 sub-agenți paraleli care estimează piața din perspective diferite: top-down, bottom-up și comparabile
2. Agentul principal sintetizează toate estimările într-un document
3. Verifică că estimările converg (diferența sub 15% = estimare solidă)

---

**4. Pasul 3 — Sondajul de validare**

1. Pe baza analizei competitivă și a estimării pieței, Claude Code creează un sondaj de maxim 10 întrebări
2. Întrebările trebuie să acopere: situația demografică, comportamentul actual, urgența problemei și disponibilitatea de plată
3. **Regula de aur:** întreabă despre trecut și prezent, nu despre viitorul ipotetic

---

**5. Pasul 4 — Pagina de test (Next.js)**

1. Cere-i lui Claude Code să creeze un proiect Next.js cu o pagină simplă de prezentare a ideii și formularul de sondaj integrat
2. Răspunsurile să fie salvate automat (Google Sheets sau fișier local)
3. Pornește serverul și verifică că formularul funcționează

---

**6. Pasul 5 — Scorul final: Merge sau nu merge?**

1. Creează un skill de analiză: `/analiza-validare` (sau similar) care citește toate datele colectate
2. Skill-ul să genereze un scor de la 0 la 100 și o concluzie clară: **Roșu** (sub 40), **Galben** (40-60), **Verde** (peste 60)
3. Citește concluzia și decide dacă mergi mai departe

---

**Cum știi că ai reușit?**
- [ ] Idee de business aleasă și descrisă în 2-3 propoziții
- [ ] Analiză competitivă cu cel puțin 5 competitori identificați, salvată în Markdown
- [ ] Estimare de piață (TAM, SAM, SOM) calculată din cel puțin 2 metode
- [ ] Sondaj de validare cu 8-10 întrebări creat
- [ ] Pagina de test Next.js funcțională cu formular și salvare răspunsuri
- [ ] Scorul final generat cu concluzia clară (roșu/galben/verde)
- [ ] (Bonus) Sondajul distribuit și primele 5+ răspunsuri colectate

---

## Lecția 2B - Cum să creezi un portofoliu de expertiză care vinde

**(Secțiunea Freelanceri și Consultanți)**

**Tema pentru acasă:** Creează un skill de portofoliu care transformă datele brute din proiectele tale în studii de caz profesionale, personalizate pe clientul potențial.

---

**1. Pregătește datele brute din proiectele tale**

1. Creează un folder `portofoliu/` în directorul tău de lucru
2. Pentru 2-3 proiecte finalizate, adună într-un subfolder pe fiecare:
   - Email-uri sau mesaje cu clientul
   - Rapoarte sau livrabile finale
   - Feedback primit de la client
   - Cifre și rezultate (chiar și aproximative)
3. Nu trebuie să fie perfect — Claude Code va extrage ce are nevoie

---

**2. Creează skill-ul de studii de caz cu Claude Code**

1. Deschide Claude Code și rulează: `/brainstorming`
2. Descrie ce vrei să construiești:
   *„Vreau să creez un skill care citește datele brute din portofoliul meu și generează un document cu studii de caz personalizat pentru un client potențial specific. Skill-ul trebuie să analizeze website-ul clientului potențial și să adapteze limbajul și studiile de caz la nevoile lui."*
3. Răspunde la întrebările de clarificare ale Claude Code

---

**3. Structura obligatorie a fiecărui studiu de caz**

Asigură-te că skill-ul generează pentru fiecare proiect toate cele 6 secțiuni:
1. **Clientul și contextul** — industria și dimensiunea companiei (anonimizat)
2. **Problema** — ce provocare avea clientul și ce a încercat fără succes
3. **Abordarea** — cum ai raționat soluția (nu ce ai livrat, ci cum ai gândit)
4. **Soluția** — ce ai livrat concret
5. **Rezultatele** — cifre, metrici, comparații înainte/după
6. **Testimonialul** — ce a spus clientul, în cuvintele lui

---

**4. Testează skill-ul pe un client potențial real**

1. Alege o companie la care ai vrea să lucrezi (sau una fictivă)
2. Rulează skill-ul cu link-ul website-ului companiei respective
3. Verifică că documentul generat:
   - Folosește limbajul și tonul din website-ul companiei
   - Evidențiază proiectele relevante pentru industria lor
   - Are secțiunea de rezultate completă cu cifre

---

**5. Iterează și îmbunătățește**

1. Identifică un studiu de caz care nu convinge și cere-i lui Claude Code să îl îmbunătățească
2. Generează și versiunea **one-pager** (prima pagină cu executive summary)
3. Adaptează tonul dacă documentul nu sună natural

---

**Cum știi că ai reușit?**
- [ ] Folder `portofoliu/` creat cu date brute din cel puțin 2 proiecte
- [ ] Skill de studii de caz creat și funcțional
- [ ] Document generat cu cele 6 secțiuni pentru fiecare studiu de caz
- [ ] Clienții din portofoliu sunt anonimizați (industrie + dimensiune, fără nume real)
- [ ] Documentul folosește limbajul de pe website-ul clientului potențial
- [ ] Secțiunea de rezultate are cifre concrete
- [ ] (Bonus) Versiunea one-pager generată și gata de trimis pe email

---

## Lecția 3A - Cum să generezi secvențe de e-mail care vând

**(Secțiunea Soloprenori)**

**Tema pentru acasă:** Creează un skill de generare de secvențe de e-mail și generează o secvență completă de 14 e-mailuri pentru serviciul tău.

---

**1. Pregătește datele despre afacerea ta**

Înainte să deschizi Claude Code, răspunde la aceste 5 întrebări:
1. **Ce vinzi?** — descrie produsul sau serviciul concret
2. **Cui vinzi?** — cine e clientul ideal și ce probleme are
3. **La ce preț?** — suma sau intervalul de preț
4. **Ce probleme rezolvă?** — durerea specifică pe care o adresezi
5. **Ce ton vrei?** — prietenos, profesional, direct, empatic

---

**2. Creează skill-ul de secvențe de e-mail**

1. Deschide Claude Code: `/brainstorming`
2. Descrie structura secvenței:
   *„Vreau să creez un skill care generează o secvență de 14 e-mailuri împărțite astfel: e-mail 1 bun venit, e-mailuri 2-7 educative (80% valoare, 20% ofertă), e-mailuri 8-10 de vânzare, e-mailuri 11-13 de urmărire și e-mailul 14 post-cumpărare. Skill-ul trebuie să citească datele din portofoliul meu și să anonimizeze companiile din studiile de caz."*
3. Răspunde la toate întrebările de clarificare

---

**3. Generează prima ta secvență**

1. Rulează skill-ul nou creat cu portofoliul tău ca input
2. Răspunde la întrebările pe care le pune (limbă, serviciu promovat, lead magnet, audiență, CTA)
3. Aprobă planul de campanie înainte de generare

---

**4. Verifică structura celor 14 e-mailuri**

Pentru fiecare e-mail, verifică că are:
- **Subiect** (2 variante) — personalizat, cu întrebare sau cifră
- **Timing** — ziua de trimitere (recomandat: la fiecare 2 zile)
- **Faza** — bun venit / educativ / vânzare / urmărire / post-cumpărare
- **CTA** — un singur îndemn la acțiune clar

---

**5. Iterează cel puțin 2-3 runde**

Nu accepta primul rezultat. Cere-i lui Claude Code să:
- Adauge mai multă poveste personală în e-mailul 3
- Genereze 3 variante de subiect pentru e-mailul de vânzare
- Scurteze e-mailurile educative la maxim 220 de cuvinte
- Ajusteze tonul dacă nu sună natural

---

**Greșeli de evitat**
- Nu da context insuficient — cu cât mai multe detalii despre afacerea ta, cu atât e-mailurile vor fi mai specifice
- Nu trimite prea des — respectă timing-ul la fiecare 2 zile
- Nu pune prea multe CTA-uri într-un e-mail — unul singur, clar

---

**Cum știi că ai reușit?**
- [ ] Skill de secvențe de e-mail creat și funcțional
- [ ] Secvență completă de 14 e-mailuri generată
- [ ] Fiecare e-mail are subiect, timing, fază și CTA
- [ ] E-mailurile educative respectă regula 80% valoare / 20% ofertă
- [ ] Companiile din studiile de caz sunt anonimizate
- [ ] Cel puțin 2 runde de iterație făcute
- [ ] 3 variante de subiect generate pentru e-mailul de vânzare
- [ ] (Bonus) Secvența importată în platforma ta de email marketing (Mailchimp, ConvertKit etc.)
