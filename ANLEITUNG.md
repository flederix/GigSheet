# GigSheet online stellen (GitHub Pages) – Schritt für Schritt

Dateien in diesem Ordner:
- gigsheet.html – die ganze App
- index.html – kleine Weiterleitung auf gigsheet.html (damit die Adresse ohne Dateinamen funktioniert)
- manifest.webmanifest, sw.js, icon-*.png, icon.svg – machen die App installierbar und offline-fähig
- docs/ – Ordner mit `GigSheet Design.pdf` und `GigSheet Handbuch.pdf` (Dokumentation, wird von der App nicht gebraucht)

## A) Online stellen mit GitHub Pages (kostenlos, ca. 10 Minuten)

1. Konto anlegen auf https://github.com (falls noch keins da ist).
2. Oben rechts "+" → "New repository". Name z. B. `gigsheet`, "Public" wählen, "Create repository".
   (Das Repository enthält nur die App, keine Songs. Deine Songs bleiben im Browser.)
3. Auf der neuen Seite "uploading an existing file" anklicken.
4. ALLE Dateien aus dem Ordner (gigsheet.html, index.html, manifest.webmanifest, sw.js, icon.svg, icon-180.png, icon-192.png, icon-512.png) in das Fenster ziehen, dazu den Ordner `docs` (ganzen Ordner ziehen), und unten "Commit changes" klicken.
5. Oben "Settings" → links "Pages". Bei "Branch" `main` und `/ (root)` wählen → "Save".
6. Nach 1–2 Minuten steht oben auf der Pages-Seite die Adresse:
   `https://DEIN-NAME.github.io/gigsheet/`
   Diesen Link kannst du an Freunde schicken.

Alternative ohne GitHub: auf https://app.netlify.com/drop den ganzen Ordner ins Fenster ziehen, fertig (Adresse wird sofort angezeigt).

## B) Als App installieren (Mac, Windows, iPad)

- Mac/Windows mit Chrome oder Edge: Adresse öffnen → in der Adressleiste rechts das Symbol "Installieren" (oder Menü → "GigSheet installieren"). Danach liegt die App im Startmenü bzw. Launchpad und öffnet sich in eigenem Fenster.
- iPad/iPhone mit Safari: Teilen-Symbol → "Zum Home-Bildschirm".
- Safari am Mac (ab Version 17): Menü "Ablage" → "Zum Dock hinzufügen".

Wichtig: Beim allerersten Öffnen braucht die App einmal Internet. Dabei lädt sie die Schrift und die PDF-Bibliothek und merkt sie sich. Danach funktioniert sie auch ohne Netz, z. B. auf der Bühne. Am besten vor dem Auftritt einmal mit Internet öffnen.

## C) Wichtig zu den Daten

- Die Songs liegen NUR im Browser des jeweiligen Geräts. Jeder Freund hat seine eigene Bibliothek.
- Wer Browserdaten/Website-Daten löscht, verliert seine Songs. Deshalb regelmäßig in der Seitenleiste unter "Sicherung" auf "Sichern" klicken und die Datei aufbewahren.
- Songs auf ein anderes Gerät bringen: dort "Sichern", auf dem Zielgerät "Import".
- Der Browser-Speicher gilt pro Adresse. Wer die App über die installierte Version und im normalen Browser nutzt, kann zwei getrennte Bibliotheken haben. Daher: eine Variante wählen.

## D) Updates einspielen

Neue gigsheet.html (oder das ganze Paket) in dasselbe GitHub-Repository hochladen ("Add file" → "Upload files", gleiche Dateinamen werden ersetzt). Beim nächsten Öffnen mit Internet holt sich die App die neue Version. Falls nicht sofort: Seite einmal neu laden.

## E) Kurz geprüft / nicht geprüft

Geprüft: Installierbarkeit, Offline-Speicher der App-Dateien, Sicherungs-Download.
Nicht geprüft: PDF-Export in der installierten App, Installation auf Mac/Windows/iPad selbst. Bitte einmal ausprobieren und mir sagen, wenn etwas hakt.
