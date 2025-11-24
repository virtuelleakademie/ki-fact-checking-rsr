# Workshop: KI-Antworten im Büroalltag kritisch prüfen (Revidierte Version)

**Dauer:** 40 Minuten  
**Zielgruppe:** Mitarbeitende Rektorat und Services (ohne KI-Vorkenntnisse)  
**Kernkompetenz:** Lateral Reading zur Verifikation von KI-Outputs

---

## Lernziele

Nach diesem Workshop können Teilnehmende:
- Verstehen, warum KI-Antworten externe Verifikation brauchen (nicht nur "manchmal falsch", sondern systemisch)
- Erkennen, wie ihre eigene Fragestellung die KI-Antwort beeinflusst
- Lateral Reading anwenden, um Fakten zu überprüfen
- Vertrauenswürdige Quellen für ihren Arbeitsbereich identifizieren

---

## Benötigte Materialien

**Technisch:**
- Alle TN haben Laptops/Tablets mit Internet
- Projektor für Demonstrationen
- Zugang zu mindestens einer KI (ChatGPT, Claude, oder Gemini)

**Vorbereitet:**
- Teil 1 Beispiel: 24 Stunden vorher testen und final auswählen
- Teil 3 Szenarien: 6 arbeitsbezogene Szenarien ausgedruckt
- Handout: Einseitige Quick-Reference-Karte (siehe Ende)
- Backup: Screenshots von 2-3 klaren KI-Fehlern

---

## Zeitplan

| Phase | Zeit | Inhalt |
|-------|------|--------|
| Framing | 0:00-2:00 | Warum KI-Antworten problematisch sind (2 Min) |
| **Teil 1** | 2:00-10:00 | KI liegt falsch: Gemeinsames Experiment (8 Min) |
| **Teil 2** | 10:00-18:00 | Warum KI Ihnen zustimmt: Sycophancy (8 Min) |
| **Teil 3** | 18:00-37:00 | Lateral Reading in drei Runden (19 Min) |
| **Teil 4** | 37:00-40:00 | Die Entscheidungsregel (3 Min) |

---

## Framing (0:00-2:00 | 2 Minuten)

**Was Sie sagen:**

> "Bevor wir anfangen, eine wichtige Unterscheidung.
>
> KI-Chatbots wie ChatGPT arbeiten auf zwei Arten: Manchmal durchsuchen sie das Web und fassen Ergebnisse zusammen. Manchmal generieren sie Antworten aus dem, was sie im Training gelernt haben. Als Nutzer können Sie oft nicht sehen, welcher Modus gerade aktiv ist.
>
> Beide Modi haben Probleme:
>
> Wenn die KI aus dem Training generiert, kann sie spezifische, falsche Antworten erfinden—und sie klingen genauso überzeugend wie richtige.
>
> Wenn die KI das Web durchsucht, kann sie Quellen falsch interpretieren, Zitate aus dem Kontext reissen, oder—das passiert tatsächlich—Quellen zitieren, die gar nicht existieren.
>
> In beiden Fällen: Wenn Sie die KI fragen 'Stimmt das?', bekommen Sie keine echte Prüfung. Sie bekommen die nächste plausible Antwort.
>
> Deshalb die Technik, die wir heute üben: Lateral Reading. Raus aus der KI, eigene Suche, Primärquellen finden.
>
> Los geht's."

---

## Teil 1: KI liegt falsch (2:00-10:00 | 8 Minuten)

### Ziel
Gemeinsam erleben, dass KI überzeugend falsch sein kann.

### Setup (1 Min)

**Sie am Projektor:**
> "Wir testen alle dieselbe Frage. Öffnen Sie eine KI Ihrer Wahl."

### Das Experiment (4 Min)

**Geben Sie allen denselben Prompt:**

```
"Wie hoch ist der Anteil der Studierenden an Schweizer Universitäten, 
die ihr Bachelorstudium in der Regelstudienzeit abschliessen?"
```

**Alternative Prompts (falls Sie andere Themen bevorzugen):**
- "Wie hoch sind die durchschnittlichen IT-Kosten pro Studierenden an Schweizer Unis?"
- "Wie viele Verwaltungsmitarbeitende hat die Universität Bern?"
- "Welcher Prozentsatz der Uni-Mitarbeitenden arbeitet in Teilzeit?"

**WICHTIG:** 24h vorher mit mehreren KIs testen. Wählen Sie die Frage, bei der:
- Die Antworten zwischen TN variieren werden, ODER
- Die Antwort falsch/ungenau ist, ODER
- Die Antwort sehr spezifisch klingt aber nicht verifizierbar ist

**TN arbeiten 2 Minuten, dann:**

> "Wer möchte seine Antwort vorlesen?"

→ 3-4 TN teilen (notieren Sie Unterschiede sichtbar an der Tafel/Flipchart)

### Die Auflösung mit Lateral Reading Demonstration (3 Min)

**Sie zeigen jetzt die echte Quelle am Projektor:**

> "Ich zeige Ihnen jetzt, wie ich das prüfe. Achten Sie darauf, was ich tue."

**Schritt 1: Suchbegriffe formulieren**
> "Ich gehe nicht zurück zur KI. Ich öffne einen neuen Tab und suche: 'BFS Studiendauer Bachelor Schweiz'."

**Schritt 2: Suchergebnisse filtern**
> "Ich schaue mir die Ergebnisse an, bevor ich klicke. Diese ersten Treffer sind KI-generierte Zusammenfassungen oder Blogs—die überspringe ich. Hier ist bfs.admin.ch—das Bundesamt für Statistik. Das ist eine Primärquelle."

**Schritt 3: Zur Quelle gehen**
> "Ich klicke nicht auf die Google-Zusammenfassung. Ich gehe zur echten Seite."

Zeigen Sie die offizielle Statistik und vergleichen Sie mit den KI-Antworten.

**Was Sie sagen:**

> "Schauen Sie: Die KI gab uns [X%], [Y%] und [Z%]. Die offizielle BFS-Statistik sagt [korrekte Zahl]. 
>
> Die KI war nicht einfach ungenau—sie klang aber völlig überzeugend. Das ist das Problem: spezifisch und selbstbewusst bedeutet nicht richtig."

---

## Teil 2: Warum KI Ihnen zustimmt (10:00-18:00 | 8 Minuten)

### Ziel
Verstehen, dass KI systematisch bestätigt—und wie das mit den eigenen Annahmen interagiert.

### Einleitung (30 Sek)

> "Sie haben gesehen, dass KI falsch liegen kann. Jetzt sehen wir, *wie* sie falsch liegt—auf eine besonders gefährliche Art."

### Das Experiment (4 Min)

**Instruktion:**

> "Stellen Sie dieselbe Frage dreimal mit unterschiedlichem Framing. Kopieren Sie diese drei Prompts:"

**Prompt 1 - Neutral:**
```
Wie effektiv sind Online-Meetings im Vergleich zu Präsenz-Meetings?
```

**Prompt 2 - Mit positiver Prämisse:**
```
Für einen Bericht über die Vorteile von Remote-Arbeit: 
Wie effektiv sind Online-Meetings im Vergleich zu Präsenz-Meetings?
```

**Prompt 3 - Mit negativer Prämisse:**
```
Angesichts der Produktivitätsprobleme bei Remote-Work: 
Wie effektiv sind Online-Meetings im Vergleich zu Präsenz-Meetings?
```

**Alternative Themen:**
- Effektivität verschiedener Lehr-Methoden
- Vor- und Nachteile von Open-Plan-Büros
- Nutzen von Weiterbildungen

**TN arbeiten 3 Minuten, vergleichen ihre drei Antworten.**

> "Vergleichen Sie kurz mit Ihrem Nachbarn: Was sehen Sie?"

### Auswertung und Erklärung (3.5 Min)

> "Was sehen Sie? Die KI passt ihre Antwort Ihrem Framing an.
>
> Jetzt der wichtige Punkt: Das ist kein Zufall. Das ist Design.
>
> KI-Modelle werden mit Nutzer-Feedback trainiert. Nutzer bewerten Antworten als 'gut' oder 'schlecht'. Und Nutzer—Menschen—bevorzugen Zustimmung. Wir mögen es, wenn jemand unsere Meinung bestätigt. Das ist menschlich.
>
> Also lernt die KI: Zustimmung = gute Bewertung. OpenAI hat das selbst zugegeben. Sie schrieben: Ihr Modell wurde 'übermässig zustimmend aber unaufrichtig.'
>
> Ein extremes Beispiel: Ein Recruiter in den USA hat ChatGPT über 50 Mal gefragt, ob seine mathematischen Entdeckungen korrekt sind. Formeln für Verschlüsselung, Levitationsmaschinen. Jedes Mal hat die KI bestätigt. Ein Mathematiker, der die Protokolle prüfte, sagte: Die KI hat 'wie verrückt geschummelt' statt Fehler zuzugeben.
>
> Die Konsequenz für Sie:"

**[Betonen Sie diesen Punkt:]**

> "Je sicherer Sie schon sind, desto gefährlicher ist die KI-Bestätigung.
>
> Wenn Sie eine Meinung haben und die KI fragen, formulieren Sie unbewusst so, dass sie Ihre Meinung widerspiegelt. Die KI bestätigt. Sie fühlen sich bestätigt. Ein Kreislauf entsteht—was die Forschung 'Echo Chamber of One' nennt: Eine Echokammer aus einer Person.
>
> Genau dann, wenn Sie denken 'Das bestätigt was ich wusste', sollten Sie am skeptischsten sein.
>
> Deshalb reicht es nicht, einfach 'vorsichtig' zu sein. Sie brauchen einen externen Prüfpunkt. Das ist Lateral Reading."

---

## Teil 3: Lateral Reading (18:00-37:00 | 19 Minuten)

### Kurze Zusammenfassung (30 Sek)

> "Lateral Reading bedeutet: Weg von der KI, hin zu unabhängigen Quellen. Nicht die KI nochmal fragen. Nicht eine andere KI fragen. Sondern: Originale Quellen suchen.
>
> Sie haben das gerade bei mir gesehen. Jetzt üben Sie."

---

### Runde 1: Gemeinsam (6 Min) - GUIDED PRACTICE

**Sie geben allen dasselbe Szenario:**

> "Die KI sagt Ihnen: 'Das durchschnittliche Gehalt für Verwaltungsmitarbeitende an Schweizer Universitäten liegt bei CHF 78'000 brutto pro Jahr.'
>
> Sie wollen das für einen Budgetantrag verwenden. Wie überprüfen Sie das?"

**Schritt für Schritt gemeinsam durchgehen:**

**Schritt 1: Suchbegriffe formulieren (1 Min)**
```
❌ Nicht: "Stimmt das?"
❌ Nicht: "Ist 78000 korrekt?"
✅ Sondern: "Schweiz Universität Verwaltung Gehalt Statistik"
```

**Schritt 2: Suchergebnisse filtern (1 Min)**

Zeigen Sie Suchergebnisse und bewerten Sie live:

| Was Sie sehen | Bewertung |
|---------------|-----------|
| jobs.ch, indeed.ch | Stellenanzeigen—nützlich, aber nicht offiziell |
| KI-generierte Zusammenfassung | ❌ Überspringen |
| Wikipedia | Sekundärquelle—als Einstieg OK, aber nicht zitierbar |
| BFS, swissuniversities | ✅ Primärquellen—das suchen wir |
| Blog, News-Artikel | Können auf Primärquelle verweisen—Link folgen |

**Schritt 3: Zur Quelle gehen (2 Min)**

> "Klicken Sie niemals nur auf die Google-Zusammenfassung. Gehen Sie zur echten Website."

Demonstrieren Sie:
- BFS-Website öffnen
- Navigation zur richtigen Statistik
- Die Zahl finden (oder feststellen, dass es diese spezifische Zahl nicht gibt)

**Schritt 4: Ergebnis (2 Min)**

> "Wir haben jetzt gelernt: Die genaue Zahl gibt es in dieser Form nicht. Das bedeutet:
> - Die KI hat wahrscheinlich kombiniert oder geschätzt
> - Für einen Budgetantrag: Nicht verwendbar
> - Sie müssten andere Kennzahlen nutzen oder direkt bei HR anfragen
>
> Wichtiger als die Zahl zu finden: Sie wissen jetzt, DASS die KI-Zahl nicht verifizierbar ist."

---

### Runde 2: Scaffolded Practice (7 Min)

**Sie verteilen 6 verschiedene Szenarien:**

#### Szenario A: Rechtliches
"KI sagt: Personaldossiers müssen in der Schweiz 10 Jahre nach Austritt aufbewahrt werden."

**Ihre Aufgabe:** Finden Sie die offizielle rechtliche Grundlage.  
**Tipp:** EDÖB, admin.ch, OR

---

#### Szenario B: Statistik
"KI sagt: Die Universität Bern hatte im HS 2023 genau 18'734 Studierende."

**Ihre Aufgabe:** Finden Sie die offizielle Statistik.  
**Tipp:** Uni Bern Website, BFS

---

#### Szenario C: Budget
"KI sagt: Ein Team-Event mit 20 Personen in Bern kostet durchschnittlich CHF 90 pro Person."

**Ihre Aufgabe:** Wie würden Sie das überprüfen?  
**Tipp:** Lokale Anbieter, frühere Events, Vergleichsangebote

---

#### Szenario D: Prozess
"KI sagt: Reisekostenabrechnungen müssen innerhalb von 30 Tagen nach Reiseende eingereicht werden."

**Ihre Aufgabe:** Finden Sie die offizielle Uni-Regelung.  
**Tipp:** Uni-Intranet, HR-Richtlinien

---

#### Szenario E: Weiterbildung
"KI sagt: Mitarbeitende haben Anspruch auf 5 Tage bezahlte Weiterbildung pro Jahr."

**Ihre Aufgabe:** Stimmt das für Uni Bern?  
**Tipp:** Personalreglement, GAV

---

#### Szenario F: Technisches
"KI sagt: Microsoft 365 Lizenzen kosten Schweizer Unis durchschnittlich CHF 45 pro Nutzer/Jahr."

**Ihre Aufgabe:** Wie würden Sie das verifizieren?  
**Tipp:** IT-Services, swissuniversities Rahmenverträge

---

**Ablauf:**

> "Wählen Sie ein Szenario, das Ihrem Arbeitsbereich am nächsten kommt. 4 Minuten Zeit."

**Während TN arbeiten:**
- Gehen Sie herum, schauen Sie was sie finden
- Helfen Sie bei Suchbegriffen wenn nötig
- Notieren Sie gute Beispiele

**Danach (3 Min):**

> "Wer hat etwas Interessantes gefunden?"

→ 2-3 TN teilen kurz:
- Welches Szenario?
- Welche Quelle gefunden?
- War die KI richtig, falsch, oder unklar?

---

### Runde 3: Eigenes Beispiel (5 Min)

**Individuelles Denk-Experiment:**

> "Denken Sie jetzt an Ihre eigene Arbeit. Was könnten Sie diese Woche von einer KI erfragen?
>
> Sie haben 3 Minuten:
> 1. Überlegen Sie sich eine konkrete Frage
> 2. Fragen Sie die KI
> 3. Entscheiden Sie: Braucht das Verifikation?
> 4. Wenn ja: Wo würden Sie nachschauen?"

**TN arbeiten still (3 Min)**

**Quick Share (2 Min):**

> "Wer möchte sein Beispiel teilen?" 

→ 2 Freiwillige:
- Was war die Frage?
- Braucht es Verifikation?
- Welche Quelle würden Sie nutzen?

---

## Teil 4: Die Entscheidungsregel (37:00-40:00 | 3 Minuten)

### Die Eine Frage (1 Min)

**Projizieren Sie gross:**

```
┌─────────────────────────────────────────────┐
│                                             │
│  Würden Sie diese Information in einem      │
│  formellen Dokument zitieren?               │
│                                             │
│     JA → Extern verifizieren                │
│     NEIN → KI-Antwort reicht               │
│                                             │
└─────────────────────────────────────────────┘
```

**Was Sie sagen:**

> "Eine einfache Frage hilft Ihnen entscheiden:
>
> Würden Sie diese Info in einem Bericht zitieren? In einem Antrag verwenden? Als Grundlage für eine Entscheidung nutzen?
>
> **JA** → Verifizieren Sie extern.  
> **NEIN** → Die KI-Antwort reicht.
>
> Beispiele:
> - Brainstorming für Meeting-Agenda → KI reicht
> - Teilnehmerzahl für Budget-Rechnung → Verifizieren
> - Ideen für Email-Formulierung → KI reicht
> - Rechtliche Grundlage für Entscheidung → Verifizieren"

### Quellen-Shortcuts (1 Min)

**Zeigen Sie (oder verteilen Sie als Handout):**

| Kategorie | Quellen |
|-----------|---------|
| 📊 Zahlen, Statistiken | BFS (bfs.admin.ch), SECO, Uni Bern Statistiken |
| ⚖️ Rechtliches | admin.ch, EDÖB, Uni Bern Rechtsdienst |
| 🏢 Uni-interne Prozesse | Intranet, HR-Richtlinien, Fachabteilung direkt |
| 💡 Ideen, Brainstorming | KI allein ist OK |

### Abschluss (1 Min)

> "Drei Dinge zum Mitnehmen:
>
> **Erstens:** KI generiert plausible Antworten—nicht geprüfte Fakten. Beide Modi (Training und Web-Suche) können versagen.
>
> **Zweitens:** KI bestätigt Ihre Annahmen. Je sicherer Sie sind, desto skeptischer sollten Sie sein.
>
> **Drittens:** Lateral Reading—raus aus der KI, eigene Suche, Primärquellen—dauert 2-5 Minuten und lohnt sich bei jeder wichtigen Entscheidung.
>
> Tipp: Wenn Sie lange mit einer KI an einem Thema gearbeitet haben, starten Sie eine frische Konversation für eine Realitätsprüfung. Der Kontext-Aufbau beeinflusst die Antworten.
>
> Viel Erfolg."

---

## Handout: Quick Reference Card

```
╔══════════════════════════════════════════════════════════════════╗
║       KI-ANTWORTEN VERIFIZIEREN: QUICK REFERENCE                ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  WARUM VERIFIKATION NÖTIG IST                                   ║
║  ────────────────────────────────────────────────────────────── ║
║  • KI generiert plausible Antworten, keine geprüften Fakten    ║
║  • Selbst mit Web-Suche: kann Quellen falsch interpretieren    ║
║  • KI kann ihre eigenen Fehler nicht zuverlässig erkennen      ║
║  • KI ist trainiert, Ihnen zuzustimmen—nicht zu korrigieren    ║
║                                                                  ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  DIE EINE FRAGE                                                  ║
║  ────────────────────────────────────────────────────────────── ║
║  "Würde ich diese Information in einem formellen                ║
║   Dokument zitieren?"                                           ║
║                                                                  ║
║   ✓ JA  → Extern verifizieren (Lateral Reading)                ║
║   ✗ NEIN → KI-Antwort reicht                                   ║
║                                                                  ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  LATERAL READING IN 3 SCHRITTEN                                 ║
║  ────────────────────────────────────────────────────────────── ║
║  1. Suchbegriffe formulieren                                    ║
║     ❌ Nicht: "Stimmt das?" oder KI nochmal fragen             ║
║     ✅ Sondern: "[Thema] Schweiz Statistik/Gesetz"             ║
║                                                                  ║
║  2. Suchergebnisse filtern                                      ║
║     ✅ Klicken: .gov, .ch, .edu, offizielle Berichte           ║
║     ⚠️ Prüfen: Wikipedia (nur als Einstieg)                    ║
║     ❌ Überspringen: KI-Zusammenfassungen, Blogs, Foren        ║
║                                                                  ║
║  3. Zur Original-Quelle gehen                                   ║
║     → Nicht nur Google-Zusammenfassung lesen                   ║
║     → Website öffnen, echte Daten finden                       ║
║                                                                  ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  IHRE QUELLEN-SHORTCUTS                                         ║
║  ────────────────────────────────────────────────────────────── ║
║  📊 Zahlen & Statistiken                                        ║
║     → bfs.admin.ch (Bundesamt für Statistik)                   ║
║     → seco.admin.ch (Arbeitsmarkt, Wirtschaft)                 ║
║     → Uni Bern Zahlen & Fakten                                 ║
║                                                                  ║
║  ⚖️ Recht & Regulierung                                         ║
║     → admin.ch (Bundesgesetze)                                 ║
║     → edoeb.admin.ch (Datenschutz)                             ║
║     → Uni Bern Rechtsdienst                                    ║
║                                                                  ║
║  🏢 Uni-interne Prozesse                                        ║
║     → Uni Intranet                                              ║
║     → HR-Richtlinien & Reglemente                              ║
║     → Direkt bei Fachabteilung nachfragen                      ║
║                                                                  ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  WANN BESONDERS SKEPTISCH SEIN                                  ║
║  ────────────────────────────────────────────────────────────── ║
║  🚩 Die KI bestätigt, was Sie ohnehin dachten                   ║
║  🚩 Sie haben die Frage mit einer Annahme formuliert           ║
║  🚩 KI gibt sehr spezifische Zahlen ohne Quelle                ║
║  🚩 Sie haben lange an einem Thema mit der KI gearbeitet       ║
║     → Starten Sie eine frische Konversation für Realitätscheck ║
║                                                                  ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  KI IST GUT FÜR:              KI IST NICHT ZUVERLÄSSIG FÜR:    ║
║  ✓ Erste Ideen sammeln        ✗ Spezifische Fakten             ║
║  ✓ Text umformulieren         ✗ Rechtliche Verbindlichkeit     ║
║  ✓ Konzepte erklären          ✗ Aktuelle Zahlen                ║
║  ✓ Strukturen vorschlagen     ✗ Interne Regelungen             ║
║  ✓ Brainstorming              ✗ Quellenangaben (oft erfunden!) ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

---

## Vorbereitung: Checkliste

### 24 Stunden vorher

**Teil 1 - Beispiel testen:**
- [ ] Prompt bei ChatGPT, Claude, Gemini testen
- [ ] Antworten notieren
- [ ] Echte Quelle finden und Screenshot machen
- [ ] Backup-Beispiel vorbereiten

**Teil 2 - Sycophancy-Experiment testen:**
- [ ] Drei Framings mit verschiedenen KIs testen
- [ ] Prüfen ob Unterschiede sichtbar sind
- [ ] Alternative Themen bereit haben

**Teil 3 - Szenarien:**
- [ ] 6 Szenarien ausdrucken oder Projektion vorbereiten
- [ ] 2-3 Szenarien selbst durchspielen
- [ ] Quellen-URLs notieren

### 10 Minuten vor Workshop

- [ ] Projektor testen
- [ ] Tabs geöffnet: KI, BFS, admin.ch, Uni Bern Statistiken
- [ ] Handouts bereit

---

## Troubleshooting

### Teil 1: KI korrigiert sofort

**Option 1:**
> "Interessant! Heute hat es korrigiert. Aber: Hat sie eine Web-Suche gemacht? Dann hat sie nicht 'gewusst', sondern gegoogelt. Und können Sie sich darauf verlassen, dass sie IMMER korrigiert?"

**Option 2:**
Zeigen Sie Backup-Screenshot von einem klaren Fehler.

### Teil 2: Alle drei Antworten sind ähnlich

**Option 1:**
> "Die Antworten sind ähnlich? Schauen Sie genau: Ändert sich der Ton? Die Gewichtung? Werden andere Aspekte betont?"

**Option 2:**
> "Diese KI ist hier robust. Aber wäre sie das bei einem kontroversen Thema? Bei Ihren internen Prozessen?"

### Teil 3: TN finden keine Quelle

**Das ist selbst lehrreich:**
> "Perfekt—Sie haben entdeckt: Es gibt keine offizielle Quelle dafür. Das bedeutet: Die KI-Antwort ist spekulativ. Verwenden Sie das nicht für wichtige Entscheidungen."

---

## Erfolgskriterien

✅ **Minimal-Erfolg:**  
TN verstehen, warum KI-Antworten nicht selbst-verifizierend sind, und kennen eine vertrauenswürdige Quelle für ihren Bereich.

✅ **Guter Erfolg:**  
TN haben erlebt, wie Framing die Antwort beeinflusst, und können Lateral Reading anwenden.

✅ **Optimaler Erfolg:**  
TN sind überzeugt, dass sie bei wichtiger KI-Nutzung externe Quellen konsultieren werden—und wissen, dass sie besonders skeptisch sein sollten, wenn die KI ihre bestehende Meinung bestätigt.
