# Room Layout Pro – Grundriss-Skizze

Einfaches Grundriss-Programm für den Browser, gemacht fürs iPad mit Apple Pencil.

- Wände mit dem Stift zeichnen – Linien werden automatisch begradigt (0°/45°/90°)
- Geschlossene Formen werden zu Räumen mit Fläche in m²; kleine geschlossene Formen (bis 90 cm) werden zu Säulen (eckig oder rund)
- Abgerundete Ecken beim Zeichnen in einem Zug werden zu sauberen Ecken
- Maße per Eingabe setzen (Innen- oder Achsmaß)
- Säulen, Schornstein, Treppe und Wandvorsprung als Bauteile
- Raumvorlagen: Rechteck, Quadrat, L/T/U-Form, Dreiecke, Trapez, Erker, Sechseck …
- Türen und Fenster rasten in Wänden ein
- Standardmöbel aus dem Menü (Wohnen, Schlafen, Küche, Bad, Arbeiten)
- Ausgewählte Wände, Türen, Fenster, Möbel und Räume per Stift oder Finger verschieben (Wände auch zentimetergenau); Endpunkt einer ausgewählten Wand ziehen ändert Länge und Winkel
- Flächen farbig füllen (10 Farben) und Bodenmuster (Parkett, Fliesen, Dielen); Möbel einfärben
- Helle und dunkle Darstellung (Mond-Symbol oben rechts)
- Bibliothek mit Vorschaubildern für Räume, Türen, Fenster und Möbel
- Export als Bild (PNG), maßstäbliches PDF (1:50/1:100/1:200) und CAD-Datei (DXF, mm, mit Layern)
- Alles löschen (Papierkorb oben rechts, mit Rückfrage), Rückgängig/Wiederholen, automatisches Speichern im Browser

## Bedienung

| Eingabe | Aktion |
|---|---|
| Stift oder Finger ziehen | Wand zeichnen |
| Tippen | Wand, Raum oder Möbel auswählen |
| Zwei Finger | Zoomen |

Sobald ein Apple Pencil benutzt wird, zeichnet nur noch der Stift und ein Finger verschiebt den Plan. Einstellbar über das Regler-Symbol → „Finger auf dem Display“.

## Online stellen (GitHub Pages)

Settings → Pages → *Deploy from a branch* → Branch `main`, Ordner `/ (root)` → Save.
Danach ist die App unter `https://<benutzername>.github.io/room-layout-pro/` erreichbar.

Die App besteht aus `index.html` und `jspdf.umd.min.js` (jsPDF 2.5.1, MIT-Lizenz, für den PDF-Export). Kein Build-Schritt nötig.
