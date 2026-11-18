# GigSheet

🇬🇧 [English](#english) · 🇩🇪 [Deutsch](#deutsch)

---

## English

A browser-based tool for bands to turn lyrics into gig-ready chord sheets, organise them into setlists and export one-page A4 PDFs for iPad or print. No account, no server: everything runs in your browser and works offline once installed.

### Features
- **Text, Editor, Sheet (A4) and Setlist** tabs, each with a compact, collapsible toolbar
- Place chords over lyrics with the keys 1–7 (scale degrees), custom chords and slash bass notes, drag and drop chords, jump word to word with Tab, chord-only lines (e.g. for intros)
- **Original and played key**, transposing, all enharmonic spellings (C#/Db, D#/Eb, …)
- Import chord sheets from Ultimate Guitar or ChordPro style text
- Repeated parts (e.g. chorus) are written once and filled in automatically
- Sheet layout: 1–2 columns, font, heading size, spacing, chord colour, highlighted chorus, auto-fit to one page, hide chords (e.g. for the drummer)
- **Setlist** page built from a library folder, reorderable, with titles and keys
- Library with folders, colours, drag and drop, search, sorting, rename/duplicate/delete
- Undo/redo, backup and import of your whole library, dark and light theme
- Installable as an app (PWA) on Mac, Windows and iPad

### Use it
Open the published page: `https://YOUR-NAME.github.io/YOUR-REPO/`

To install: in Chrome/Edge click **Install** in the address bar; on iPad use **Share → Add to Home Screen**. Open it once online so the font and PDF library are cached; after that it runs offline.

### Your data
Songs are stored only in your browser (local storage) on each device. Nothing is uploaded. Clearing site data deletes them, so use **Backup** in the sidebar regularly. To move songs to another device, back up there and use **Import** on the target.

### Run locally
Download the repository (**Code → Download ZIP**) and open `gigsheet.html`. Installation and offline mode need the page to be served over `http(s)`, for example via GitHub Pages.

### Built with
Plain HTML, CSS and JavaScript in one file, [jsPDF](https://github.com/parallax/jsPDF) for PDF export and the Inter font from Google Fonts.

### Note
The app contains no songs. Lyrics and chords you enter remain subject to the rights of their owners.

---

## Deutsch

Ein Browser-Werkzeug für Bands: aus Liedtexten werden bühnentaugliche Chord Sheets, die sich zu Setlists ordnen und als einseitige A4-PDFs für iPad oder Druck exportieren lassen. Kein Konto, kein Server: alles läuft im Browser und nach der Installation auch offline.

### Funktionen
- Reiter **Text, Editor, Blatt (A4) und Setlist**, jeweils mit kompakter, einklappbarer Werkzeugleiste
- Akkorde über den Text setzen mit den Tasten 1–7 (Stufen der Tonleiter), eigene Akkorde und Slash-Bass, Akkorde per Drag & Drop verschieben, mit Tab von Wort zu Wort springen, reine Akkordzeilen (z. B. fürs Intro)
- **Original- und gespielte Tonart**, Transponieren, alle enharmonischen Schreibweisen (C#/Db, D#/Eb, …)
- Chord Sheets im Stil von Ultimate Guitar oder ChordPro einlesen
- Wiederholte Teile (z. B. Refrain) einmal schreiben, der Rest wird automatisch ergänzt
- Blatt-Layout: 1–2 Spalten, Schrift, Überschriftengröße, Abstände, Akkordfarbe, hervorgehobener Refrain, Auto-Größe auf eine Seite, Akkorde ausblenden (z. B. für den Drummer)
- **Setlist** aus einem Bibliotheksordner, frei sortierbar, mit Titeln und Tonarten
- Bibliothek mit Ordnern, Farben, Drag & Drop, Suche, Sortierung, Umbenennen/Duplizieren/Löschen
- Rückgängig/Wiederholen, Sicherung und Import der gesamten Bibliothek, dunkles und helles Design
- Als App installierbar (PWA) auf Mac, Windows und iPad

### Benutzen
Die veröffentlichte Seite öffnen: `https://DEIN-NAME.github.io/DEIN-REPO/`

Installieren: In Chrome/Edge in der Adressleiste auf **Installieren** klicken, am iPad **Teilen → Zum Home-Bildschirm**. Einmal mit Internet öffnen, damit Schrift und PDF-Bibliothek zwischengespeichert werden. Danach läuft die App offline.

### Deine Daten
Songs liegen nur im Browser (lokaler Speicher) des jeweiligen Geräts. Es wird nichts hochgeladen. Wer Website-Daten löscht, verliert sie, daher regelmäßig in der Seitenleiste **Sichern** nutzen. Songs auf ein anderes Gerät bringen: dort sichern, am Ziel **Import**.

### Lokal ausführen
Repository herunterladen (**Code → Download ZIP**) und `gigsheet.html` öffnen. Installation und Offline-Modus brauchen eine Auslieferung über `http(s)`, zum Beispiel über GitHub Pages.

### Technik
Reines HTML, CSS und JavaScript in einer Datei, [jsPDF](https://github.com/parallax/jsPDF) für den PDF-Export und die Schrift Inter von Google Fonts.

### Hinweis
Die App enthält keine Songs. Texte und Akkorde, die du eingibst, unterliegen weiterhin den Rechten ihrer Urheber.
