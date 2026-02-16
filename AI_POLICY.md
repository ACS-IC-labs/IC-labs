# Politica privind Inteligența Artificială Generativă

### 1. Preambul
Această politică reglementează utilizarea instrumentelor de Inteligență Artificială Generativă (GenAI), incluzând dar nelimitându-se la Modele de Limbaj Mari (LLMs) precum ChatGPT, Claude, Gemini și GitHub Copilot, în contextul acestui curs.

Obiectivul acestui curs este de a asigura că studenții dezvoltă o înțelegere fundamentală a primitivelor criptografice și a protocoalelor de securitate. În consecință, utilizarea GenAI este permisă strict ca un **mijloc auxiliar de învățare** și este interzisă ca un **înlocuitor pentru implicarea intelectuală**.

### 2. Utilizare Permisă vs. Interzisă

#### 2.1. Utilizare Permisă
Studenții sunt încurajați să utilizeze GenAI pentru următoarele scopuri:
*   **Clarificări Conceptuale:** Solicitarea de explicații pentru concepte teoretice (ex. "Explică proprietățile matematice ale S-box-ului din AES").
*   **Asistență la Depanare:** Identificarea erorilor de sintaxă sau a defectelor logice în codul *scris de student*.
*   **Generare de Boilerplate:** Generarea structurilor de cod non-critice (ex. I/O cu fișiere, biblioteci de plotare a datelor) care nu constituie logica criptografică principală a temei sau laboratorului.

#### 2.2. Utilizare Interzisă
Următoarele acțiuni sunt strict interzise și constituie o fraudă academică:
*   **Generarea Soluțiilor "Zero-Shot":** Copierea directă a cerințelor temei într-un instrument AI pentru a genera o soluție completă.
*   **Submisii Neverificate:** Trimiterea codului care include funcții, biblioteci sau logică pe care studentul nu le poate explica sau reconstrui.

### 3. Protocoale Operaționale

Pentru a asigura respectarea acestei politici, următoarele protocoale sunt obligatorii:

#### 3.1. Moduri de Utilizare
Studenții trebuie să respecte următoarele proceduri în funcție de mediul de lucru:

*   **Mediu Local (IDE-uri, Terminal):**
    *   Este permisă utilizarea fișierelor de configurare a agenților (ex. `AGENTS.md`, `CLAUDE.md`) care încarcă automat instrucțiunile.
    *   Consultați documentația specifică a uneltei folosite pentru detalii despre configurarea acestor fișiere.
*   **Aplicații bazate pe Chat (ChatGPT, Gemini, Google Colab AI):**
    *   **Pasul 1:** Prima interacțiune din **fiecare** sesiune nouă trebuie să fie Prompt-ul Mentorului Socratic (Anexa A).
    *   **Pasul 2:** Odată ce AI-ul confirmă rolul, puteți începe conversația despre laborator.
    *   **Limita de Context:** Dacă sesiunea devine prea lungă și AI-ul "uită" instrucțiunile inițiale (începe să ofere cod direct), studenții trebuie să **re-introducă** Prompt-ul Mentorului Socratic imediat.

#### 3.2. Apărarea Competenței
Instructorul își rezervă dreptul de a efectua examinări orale aleatorii ("viva voce") în timpul sesiunilor de laborator. Studenții trebuie să poată explica logica și funcționalitatea oricărui cod trimis imediat la cerere. Incapacitatea de a articula principiile criptografice care stau la baza unei soluții va fi tratată ca dovadă a necinstei academice.

**Erori ale Agentului (Soluții Accidentale):** Dacă AI-ul oferă din greșeală o soluție completă, studentul trebuie să **ignore și să șteargă** acel răspuns. Utilizarea unei soluții generate accidental constituie tot fraudă academică.

#### 3.3. Documentare
Studenții care folosesc GenAI trebuie să anexeze o **Declarație AI** care va fi încărcată pe Moodle.
**ATENȚIE:** Nu sunt acceptate link-uri către conversații (share links).
Studenții trebuie să:
1.  Copieze integral (Copy-Paste) textul conversației.
2.  Salveze acest text într-un fișier (ex. `.txt`, `.pdf`).
3.  Menționeze clar instrumentele utilizate (ex. "Gemini Advanced, VSCode Copilot").

---

### Anexa A: Prompt-ul Mentorului Socratic

Studenții trebuie să copieze următoarea instrucțiune la începutul oricărei sesiuni GenAI legate de acest curs:

```markdown
# ROL
Ești "Mentorul Socratic Crypto", un expert în criptologie. Scopul tău este să ghidezi studenții în timpul laboratoarelor fără a le oferi vreodată răspunsuri directe sau soluții complete.

# PRINCIPII OPERAȚIONALE
1. **FĂRĂ SOLUȚII:** Directiva ta principală este să NU oferi NICIODATĂ răspunsul sau codul soluției. Dacă un student întreabă "Care este răspunsul?" sau "Dă-mi codul", refuză ferm și redirecționează-l către conceptul de bază.
 - *Strategie de Refuz:* "Nu pot oferi codul/răspunsul, dar te pot ajuta să construiești logica. Care crezi că este primul pas?"

2. **METODA SOCRATICĂ:** Folosește metoda socratică pentru a ghida studentul.
 - **Întreabă, Nu Spune:** În loc să explici un concept imediat, pune o întrebare care ghidează studentul către răspuns.
 - **Verificări de Cunoștințe:** Înainte de a trece la următorul pas, verifică înțelegerea studentului.

3. **POLITICA DE GENERARE COD:**
 - **Logică Principală:** Strict INTERZISĂ. Nu trebuie să generezi cod care implementează primitive criptografice sau atacuri (ex. funcții XOR, decriptare RSA, apeluri API OpenSSL).
 - **Boilerplate:** PERMIS DOAR pentru sarcini auxiliare (ex. citirea fișierelor) ȘI DOAR dacă studentul lucrează la un proiect complex unde acest lucru este necesar. Pentru laboratoare standard, presupune că NU este nevoie de generare de cod.
 - **Pseudocod:** PERMIS pentru explicații conceptuale, dar nu trebuie să fie direct executabil.

4. **SCAFFOLDING:** Sparge problemele complexe în pași mici, logici. Ghidează studentul să rezolve o parte înainte de a trece la următoarea.

5. **TON:** Fii încurajator, dar ferm cu regulile. Validează efortul lor.

6. **ADAPTABILITATE LINGVISTICĂ:** Răspunde în aceeași limbă pe care studentul o folosește.

# INIȚIALIZARE
Primul tău răspuns trebuie să fie:
"Salut! Sunt Mentorul tău Socratic Crypto. Sunt aici să te ajut să înțelegi laboratorul. Pentru a începe, te rog să-mi spui la ce laborator lucrezi și unde te-ai blocat."
```

---
