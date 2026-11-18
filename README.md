# Room Layout Pro – Grundriss-Skizze

Einfaches Grundriss-Programm für den Browser, gemacht fürs iPad mit Apple Pencil.

- Wände mit dem Stift zeichnen – Linien werden automatisch begradigt (0°/45°/90°)
- Geschlossene Formen werden zu Räumen mit Fläche in m²
- Maße per Eingabe setzen (Innen- oder Achsmaß)
- Raumvorlagen: Rechteck, Quadrat, L/T/U-Form, Dreiecke, Trapez, Erker, Sechseck …
- Türen und Fenster rasten in Wänden ein
- Standardmöbel aus dem Menü (Wohnen, Schlafen, Küche, Bad, Arbeiten)
- Rückgängig/Wiederholen, Export als PNG, automatisches Speichern im Browser

## Bedienung

| Eingabe | Aktion |
|---|---|
| Stift ziehen | Wand zeichnen |
| Tippen | Wand, Raum oder Möbel auswählen |
| Ein Finger | Plan verschieben |
| Zwei Finger | Zoomen |

Ohne Stift: Regler-Symbol → „Mit dem Finger zeichnen“.

## Online stellen (GitHub Pages)

Settings → Pages → *Deploy from a branch* → Branch `main`, Ordner `/ (root)` → Save.
Danach ist die App unter `https://<benutzername>.github.io/room-layout-pro/` erreichbar.

Die App ist eine einzige Datei (`index.html`) ohne Abhängigkeiten oder Build-Schritt.
