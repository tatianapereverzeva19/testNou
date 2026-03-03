# Teme pentru acasă — Modulul 8

---

## Lecția 0 - Content Multiplication Pipeline — Introducere

**Tema pentru acasă:** Verifică că toate tool-urile din modulele precedente funcționează și pregătește structura de foldere pentru pipeline-ul din modulul 8.

---

**1. Verifică MCP-urile**

1. Deschide Claude Code în terminal (`claude`)
2. Testează că **Replicate MCP** răspunde la comenzi (folosit pentru imagini din Modulul 5)
3. Testează că **ElevenLabs MCP** răspunde la comenzi (folosit pentru voce din Modulul 6)
4. Verifică că ai **cheia de API fal.ai** setată corect în fișierul `.env`
5. Verifică că ai **cheia de API Replicate** setată corect în `.env`

---

**2. Verifică instanța N8N**

1. Accesează `localhost:5678` (dacă rulezi local) sau URL-ul instanței tale N8N din cloud
2. Asigură-te că dashboard-ul se încarcă fără erori
3. Dacă nu pornește, repornește instanța și verifică conexiunea

---

**3. Creează structura de foldere cu Claude Code**

1. Deschide Claude Code și spune: *„Creează o structură de foldere pentru un proiect de content multiplication pipeline cu foldere pentru: strategie, articole, postări (câte un subfolder per platformă), media (imagini, audio, video) și output."*
2. Verifică că structura a fost creată corect
3. Salvează structura — o vei folosi în toate lecțiile modulului

---

**Cum știi că ai reușit?**
- [ ] Replicate MCP răspunde la comenzi din Claude Code
- [ ] ElevenLabs MCP răspunde la comenzi din Claude Code
- [ ] Cheile de API fal.ai și Replicate sunt setate în `.env`
- [ ] N8N pornit și accesibil
- [ ] Structura de foldere creată



---

## Lecția 1 - Build Your AI-Powered Content Strategy Calendar

**Tema pentru acasă:** Definește 3–5 pilari de content, alege 2–3 platforme principale și creează un content calendar pentru 2 săptămâni cu Claude Code, respectând mixul 80-15-5.

---

**1. Definește 3–5 pilari de content**

1. Deschide Claude Code și spune: *„Analizează acest business: [descrie business-ul tău în 3–5 rânduri]. Audiența mea principală este [descrie audiența]. Propune 3–5 content pillars cu 3–5 subteme pentru fiecare, plus exemple de posturi."*
2. Ajustează pilarii propuși până reflectă exact expertiza ta
3. Salvează rezultatul în `strategie/content-pillars.md` — acesta devine documentul de referință al strategiei tale

---

**2. Alege 2–3 platforme principale**

1. Cere lui Claude Code: *„Evaluează pentru [LinkedIn, Instagram, YouTube, Newsletter, X] un decision matrix pe 4 criterii: audiență (1–5), format (1–5), efort (1–5), ROI (1–5). Business-ul meu este [descriere]. Recomandă 2–3 platforme principale și 1–2 secundare."*
2. Salvează selecția în `strategie/platforme.md`

---

**3. Creează content calendar pentru 2 săptămâni**

1. Cere lui Claude Code: *„Folosind acești content pillars: [pilarii tăi]. Platformele principale: [platformele tale]. Frecvența: [ex: LinkedIn 3x/săptămână, Instagram 4x/săptămână]. Generează un content calendar pentru 2 săptămâni, cu mixul 80-15-5 (80% educațional, 15% entertaining, 5% promoțional). Format tabel: Data | Pillar | Topic | Platformă | Format | Status."*
2. Ajustează 2–3 topicuri dacă nu se potrivesc
3. Salvează în `strategie/content-calendar.md`

---

**Cum știi că ai reușit?**
- [ ] `content-pillars.md` cu 3–5 pilari, fiecare cu 3–5 subteme
- [ ] 2–3 platforme principale alese și 1–2 secundare
- [ ] `content-calendar.md` cu structura completă pe 2 săptămâni
- [ ] Calendarul respectă mixul 80% educațional / 15% entertaining / 5% promoțional
- [ ] Frecvența per platformă este realistă și sustenabilă pe 6 luni



---

## Lecția 2 - Transformă un blog post în 20+ piese de conținut

**Tema pentru acasă:** Creează un repurposing matrix complet și testează-l cu Claude Code, generând cel puțin 3 variații adaptate nativ pe platforme diferite.

---

**1. Alege sau generează materialul sursă**

- **Dacă ai un blog post existent:** folosește-l ca sursă direct
- **Dacă nu ai un blog post:** cere lui Claude Code să genereze unul de 1500 de cuvinte pe un topic relevant pentru business-ul tău, cu structura: hook → problemă → insights → acționabil → CTA

---

**2. Creează repurposing matrix-ul**

1. Creează un fișier `strategie/repurposing-matrix.md`
2. Definește specificații pentru fiecare platformă, urmând structura:

| Platformă | Format | Lungime | Ton | CTA |
|-----------|--------|---------|-----|-----|
| LinkedIn | Post text | 150–200 cuvinte | Profesional, insight-driven | Soft (întrebare) |
| Instagram | Caption + carusel | 80–120 cuvinte | Conversațional, cald | Link in bio |
| X / Twitter | Thread | 5–8 tweet-uri, 71–100 caractere/tweet | Direct, punchline | Minimal |
| Newsletter | Email | 300–500 cuvinte | Personal, ca o scrisoare | Un singur CTA clar |
| YouTube | Script how-to | 2–3 minute | Informativ, cu personalitate | Abonare |
| Podcast | Talking points | 5–7 minute | Conversațional | Menționat verbal |
| Reels / TikTok | Video script | 15–30 secunde | Energetic, rapid | CTA vocal |

3. Adaugă o secțiune **Mesaj Core** — 1–2 propoziții cu ideea centrală care trebuie să fie prezentă în toate variațiile

---

**3. Testează matrix-ul cu Claude Code**

1. Deschide Claude Code și spune: *„Ia acest blog post [sau: generează un blog post despre [topic]]. Aplică repurposing matrix-ul din [calea fișierului]. Generează: 1 post LinkedIn, 1 caption Instagram, 1 thread X și 1 email newsletter."*
2. Citește fiecare variație și verifică că:
   - Mesajul core este prezent în toate
   - Tonul e adaptat platformei
   - Lungimea respectă specificațiile

---

**Cum știi că ai reușit?**
- [ ] `repurposing-matrix.md` complet cu specificații pentru minim 7 tipuri de postări
- [ ] Mesajul core definit în 1–2 propoziții
- [ ] Cel puțin 3 variații generate cu Claude Code (platforme diferite)
- [ ] Variațiile respectă lungimea și tonul specificat per platformă
- [ ] Același mesaj de bază este prezent în toate variantele, fără contradicții



---

## Lecția 3 - Content Generation Engine: De la Brief la Conținut în Minute

**Tema pentru acasă:** Scrie un brief de 2–3 rânduri, generează un blog post cu Claude Code, aplică repurposing matrix și fă review pe cel puțin 5 variații.

---

**1. Scrie un brief de 2–3 rânduri**

1. Scrie un brief care include: **topicul** (ce vrei să spui), **audiența** (cine citește) și **scopul** (ce vrei să facă cititorul după)
2. Exemplu: *„Un articol despre de ce freelancerii câștigă mai mult când folosesc Claude Code pentru automatizări. Audiență: freelanceri tehnici și consultanți. Scop: să înceapă să exploreze Claude Code."*
3. Salvează brief-ul în `articole/brief-[slug].md`

---

**2. Configurează BraveSearch MCP și generează blog postul**

1. Dacă nu ai BraveSearch MCP configurat, urmează pașii din demo: accesează `api.search.brave.com`, creează o cheie de API gratuită (2000 căutări/lună) și spune lui Claude Code: *„Configurează MCP-ul de BraveSearch cu cheia asta în `.mcp.json` în folderul curent."*
2. Cere lui Claude Code: *„Folosind BraveSearch pentru keyword research, scrie un blog post de 1500 de cuvinte pe baza acestui brief: [brief-ul tău]. Optimizează pentru SEO: keyword în titlu, în primii 100 de cuvinte și în cel puțin 2 headings. Structura: hook → problemă → insights → acționabil → CTA. Salvează în `articole/`."*
3. Verifică că articolul respectă structura și că keyword-ul apare natural

---

**3. Aplică repurposing matrix**

1. Cere lui Claude Code: *„Aplică repurposing matrix-ul din `strategie/repurposing-matrix.md` pe articolul din `articole/`. Generează toate variațiile: 3 posturi LinkedIn, 5 captionuri Instagram, 2 thread-uri X, 1 email newsletter, 2 scripturi YouTube și 3 scripturi Reels. Organizează-le în `postări/` cu câte un subfolder per platformă."*
2. Verifică structura de foldere generată

---

**4. Fă review în 3 întrebări**

Pentru cel puțin 5–6 variații, verifică:
1. Este mesajul de bază consistent cu articolul sursă?
2. Este tonul potrivit pentru platformă?
3. Faptele și cifrele din text sunt corecte?

Corectează variațiile care nu trec verificarea înainte de a merge mai departe.

---

**Cum știi că ai reușit?**
- [ ] Brief de 2–3 rânduri salvat în `articole/`
- [ ] Blog post de minim 1500 cuvinte cu structura hook / problemă / insights / acționabil / CTA
- [ ] Keyword principal în titlu, în primii 100 cuvinte și în cel puțin 2 headings
- [ ] Minim 15 piese de text generate și organizate pe platformă în `postări/`
- [ ] Mesaj core consistent în toate variațiile
- [ ] Review făcut pe cel puțin 5–6 variații și corectat ce nu era ok



---

## Lecția 4 - Content Multiplication with Multimedia Generation

**Tema pentru acasă:** Alege un post din lecția precedentă și generează pentru el o imagine profesională, un audio clip și un video scurt — orchestrate din Claude Code.

---

**1. Alege postul sursă**

1. Deschide folderul `postări/` generat în lecția 3
2. Alege un singur post — de preferință unul de LinkedIn sau Instagram — care are deja textul complet
3. Notează calea completă a fișierului — o vei da lui Claude Code

---

**2. Generează imaginea**

1. Cere lui Claude Code: *„Citește postarea din [calea fișierului]. Generează o imagine profesională pentru aceasta folosind Replicate MCP. Salvează în folderul `media/imagini/`."*
2. Verifică că imaginea generată este relevantă pentru conținut și că a fost salvată corect

---

**3. Generează audio-ul**

1. Cere lui Claude Code: *„Folosind ElevenLabs MCP, generează un audio clip de 30–60 secunde bazat pe postarea din [calea fișierului]. Folosește vocea [vocea ta clonată / orice voce disponibilă]. Salvează în `media/audio/`."*
2. Ascultă clipul și verifică calitatea

---

**4. Generează video-ul**

1. Cere lui Claude Code: *„Generează un video scurt de 30 secunde–1 minut pentru postarea din [calea fișierului]. Folosește HeyGen pentru avatar sau fal.ai/Veo3 pentru clip cinematic. Salvează în `media/video/`."*
2. Verifică că video-ul a fost generat și salvat corect

---

**Cum știi că ai reușit?**
- [ ] O imagine profesională generată și salvată în `media/imagini/`
- [ ] Un audio clip de 30–60 secunde generat și salvat în `media/audio/`
- [ ] Un video scurt de 30 secunde–1 minut generat și salvat în `media/video/`
- [ ] Toate fișierele sunt legate de același post sursă



---

## Lecția 5 - Multimedia Assembly: De la Fișiere la Publicare

**Tema pentru acasă:** Organizează tot output-ul din lecțiile 3 și 4, creează structura de foldere pe Google Drive cu config.json per postare și verifică că fiecare pachet este complet și gata de publicat.

---

**1. Corectează output-ul din lecțiile 3 și 4**

1. Deschide folderele `postări/` și `media/` și verifică că fiecare postare are fișierele asociate corect
2. Dacă lipsesc imagini, audio sau video pentru unele postări, generează-le înainte de a continua

---

**2. Rulează skill-ul de assembly și upload pe Google Drive**

1. Urmează demo-ul din lecție pentru a construi skill-ul de upload pe Google Drive (autentificare OAuth2 cu `credentials.json`)
2. Cere lui Claude Code: *„Uită-te pe structura din `postări/`. Uploadează toate postările pe Google Drive, în folderul [ID folder Drive]. Creează câte un subfolder per postare cu structura: `[număr]-[slug]/[platformă]/config.json`. Fiecare `config.json` trebuie să conțină: platform, caption, media\_files, schedule\_time, status (pending), post\_type și hashtag-uri."*
3. Confirmă preview-ul propus înainte de upload

---

**3. Verifică fiecare folder**

1. Deschide Google Drive și verifică că structura a fost creată corect
2. Deschide câteva fișiere `config.json` și verifică că toate câmpurile sunt completate
3. Verifică că fișierele media (imagini, video, audio) au fost uploadate alături de config

---

**Cum știi că ai reușit?**
- [ ] Toate postările din lecția 3 au fișiere media asociate
- [ ] Structura de foldere per postare și per platformă creată pe Google Drive
- [ ] Fiecare folder conține `config.json` cu caption, media\_files, schedule\_time, status și hashtag-uri
- [ ] `index.md` generat cu inventarul complet al tuturor postărilor
- [ ] Upload confirmat pe Google Drive



---

## Lecția 6 - Brand Voice & Quality Control: ADN-ul Comunicării Tale

**Tema pentru acasă:** Creează documentul de brand voice, antrenează Claude Code să-l respecte și testează quality control pe minim 5 postări din lecțiile anterioare.

---

**1. Adună materialul de referință**

1. Adună **10–20 postări** de ale tale cu cel mai mare engagement sau despre care ai primit feedback pozitiv gen *„asta sună fix ca tine"*
2. Dacă nu ai postări publicate, folosește emailuri, mesaje sau texte scrise de tine pe orice canal

---

**2. Generează documentul de brand voice**

1. Cere lui Claude Code: *„Citește aceste postări [inserează textele sau trimite fișierele]. Extrage pattern-urile de ton, vocabular, structura frazelor, nivel de umor și valori. Generează un brand voice document complet cu: definiție pentru fiecare atribut, exemple concrete (do / don't) și 3–5 exemple de propoziții on-brand."*
2. Ajustează documentul până reflectă exact cum vorbești tu
3. Salvează în `strategie/brand-voice.md`

---

**3. Generează 3 postări noi și verifică scorul**

1. Cere lui Claude Code: *„Citește `strategie/brand-voice.md`. Generează 3 postări de LinkedIn pe topicuri la alegerea ta. Scorează fiecare pe o scală de la 0 la 100 pentru consistența cu brand voice-ul. Listează ce este on-brand și ce deviază."*
2. Dacă scorul e sub 80 la oricare postare, spune lui Claude Code: *„Regenerează postarea [numărul] ținând cont de [feedback specific]. Scorează din nou."*
3. Iteratează până toate cele 3 postări au scor de minimum 80

---

**4. Testează quality control pe postările din lecțiile anterioare**

1. Alege minim 5 postări generate în lecțiile 1–4
2. Cere lui Claude Code: *„Aplică quality control pe aceste postări folosind `strategie/brand-voice.md`. Verifică 4 criterii: (1) mesaj coerent, (2) ton on-brand, (3) fapte corecte, (4) format corect pe platformă. Dă verdict per postare: Pass / Needs Fix / Rewrite."*
3. Corectează postările marcate cu *Needs Fix* sau *Rewrite*

---

**Cum știi că ai reușit?**
- [ ] `brand-voice.md` complet cu ton, vocabular, structura frazelor, umor și valori
- [ ] Brand voice chart cu 3–5 atribute, cu exemple do / don't pentru fiecare
- [ ] 3 postări noi generate cu scor de consistență de minimum 80%
- [ ] QC report pe minim 5 postări cu verdict clar (Pass / Needs Fix / Rewrite)
- [ ] Postările marcate ca Needs Fix sau Rewrite corectate



