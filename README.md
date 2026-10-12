# 🔍 Wörterdetektiv — Nomen, Verben & Adjektive erkennen

Interaktives Deutsch-Lernspiel für **Klasse 2–3, Förderunterricht und Sprachförderung**.
Die Kinder arbeiten als Detektive im freundlichen Detektivbüro und lösen „Fälle“. Dabei erkennen sie die drei Wortarten
**Nomen, Verben und Adjektive** – in Einzelwörtern und im Satz. Die Antwortknöpfe heißen immer **NOMEN / VERB / ADJEKTIV**;
die Begriffe Namenwörter, Tunwörter und Wiewörter stehen nur im Hilfetext (Lupe / „?“).

## 🗂️ Die sechs Fälle (Modi)
1. **Welche Wortart ist das?** (Die Lupe) – ein Wort, drei Antwortknöpfe. Danach kurze Erklärung.
2. **Sortiere die Beweise!** (Der Aktenschrank) – 3–4 / 5–6 / 6–8 Wortkarten in die Schubladen NOMEN / VERBEN / ADJEKTIVE sortieren (Maus-Ziehen, Finger-Ziehen **oder** Antippen, auch per Tastatur).
3. **Welches Wort gehört nicht dazu?** (Die Spurensuche) – vier Wörter, drei haben dieselbe Wortart.
4. **Wortarten im Satz** (Die Pinnwand) – „Finde das …“ (genau eine Lösung) oder „Finde alle …“ im Satz antippen. Danach stehen unter allen Wörtern ihre Wortarten.
5. **Finde das passende Wort!** (Das Notizbuch) – Bild- oder Lückenaufgaben mit genau einer passenden Lösung.
6. **Der große Wörterfall** – Mischung aus allen Aufgabenarten; nie dieselbe Art zweimal hintereinander.

Ablauf: Fall wählen → Schwierigkeit (leicht / mittel / schwer) → spielen.
**Schwer** heißt: längere und anspruchsvollere Sätze, weniger Hilfe – nie Fangfragen.

## 🧩 Fortschritt: Die Fallakte
Ein Fall endet nach **8 richtig gelösten Aufgaben**. Für jede richtige Lösung wird ein Hinweis (Fußspur, Schlüssel, Fingerabdruck, Brief, Feder, Knopf, Taschenuhr, Hut) an die Fallakte geheftet.
Am Ende: **„FALL GELÖST! – Du hast alle Hinweise gefunden.“** mit „Neuen Fall lösen“ und „Zurück zur Auswahl“.
Kein Zeitlimit, keine Punkte, keine Leben, kein Game Over, kein Highscore. Eine falsche Antwort gibt einen freundlichen Hinweis, **verrät die Lösung nicht** und bringt keinen Fortschritt.

## 🔤 Material
- **237 Wörter** (90 Nomen · 69 Verben · 78 Adjektive) in 12 Kategorien, Stufen leicht/mittel/schwer. Verben in der Grundform, Adjektive ohne Verwechslung mit Verbformen, keine Eigennamen, keine mehrdeutigen Wörter.
- **89 Sätze** (225 Fragen) ohne Eigennamen, Adverbien und trennbare Verben; Funktionswörter (Artikel, Pronomen, „und“ …) werden nie abgefragt. Sätze mit „sein/haben“ erhalten keine Verb-Frage.
- **51 Lückensätze**, **14 Verb-Szenen** und **16 Adjektiv-Bilder** (eigene SVG-Illustrationen).
- Hinweise sind nie absolut formuliert („Nomen haben immer …“ gibt es nicht); keine Wortart ist an eine feste Farbe oder Position gebunden – Knopffarben und die Lage der richtigen Antwort wechseln zufällig.
- Rundenplan: keine Wortwiederholung, ausgewogene Verteilung N/V/A, wechselnde Themen, richtige Antwort nie zweimal an derselben Stelle hintereinander.

## 🔊 Sprachausgabe
Browser-Sprachausgabe (de-DE) als reine Unterstützung. Wörter stehen immer sichtbar da. Ohne Sprachausgabe im Browser werden die Lautsprecher-Knöpfe ausgeblendet; das Spiel bleibt vollständig spielbar.

## 📱 Geräte & Bedienung
Smartboard, PC, Laptop, Tablet, Smartphone; Maus, Touch, Tastatur; Hoch- und Querformat. Alle Aufgaben passen **ohne Scrollen** (geprüft von 360×640 bis 2560×1440, Laptop ab ca. 600 px Höhe). Touch-Ziele ≥ 44 px, sichtbare Fokusrahmen, Kontraste nach WCAG AA, `prefers-reduced-motion`, Information nie nur durch Farbe.

## 🛠️ Technik
Eine einzige `index.html` (HTML, CSS, Vanilla JavaScript). Keine Frameworks, keine externen Bilder/Schriften/APIs, keine Cookies, kein Tracking, keine Datenspeicherung.
Netlify: Ordner per Drag & Drop (Build command leer, Publish directory `.`). GitHub: `index.html`, `README.md`, `.gitignore` (+ optional `arbeitsblaetter/`, `pruefung/`).

## 🖨️ Arbeitsmaterialien (`arbeitsblaetter/`, HTML + PDF)
- `teilnehmeruebersicht` – A4 quer, 30 Kinder × 10 Fälle
- `arbeitsblatt-nomen-verben-adjektive` – Wortarten ankreuzen, sortieren, „Was gehört nicht dazu?“, Lückensätze
- `arbeitsblatt-wortarten-im-satz` – Verb / Nomen / Adjektive im Satz einkreisen, Wörter in Tabelle schreiben
- jeweils zusätzlich `-loesung` (für Lehrkräfte)

## ✅ Prüfmaterial (`pruefung/`)
`pruefuebersicht.html`, `.pdf`, `.csv` – alle Wörter (Wort / Wortart / Stufe / Kategorie), Sätze (Satz / gesuchte Wortart / Lösung(en) / Stufe), Lückensätze und Bildaufgaben.

## 🧪 Qualitätssicherung
Daten- und Grammatik-Audit (Wortarten gegen Wiktionary, Funktionswort-Whitelist, genau eine Lösung je Aufgabe) · Simulation von über 200.000 Aufgaben (Rundenplan, Verteilung, keine Wiederholung, Stufen) · alle 6 Modi × 3 Stufen als volle Runden über die Oberfläche · Maus-/Touch-Ziehen + Tippen + Tastatur · Betrieb mit und ohne Sprachausgabe · Reduced Motion · Kontrastprüfung · 15 Bildschirmgrößen ohne Scrollen/Überlappung · Konsole ohne Fehler.
