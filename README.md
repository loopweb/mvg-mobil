<img src="icon.png" width="96" alt="MVG Mobil Icon">

# MVG Mobil

Die mobile Version des **Musik Video Generators (MVG)** von *Don Miguel de Cabarete*.
Einen Song mit eigenen Clips und Fotos zu einem Musikvideo verbinden, mit Schnitten auf dem Beat und direkt am Handy.

**▶ App öffnen:** https://loopweb.github.io/mvg-mobil/

Alles läuft im Browser. Musik, Clips und Fotos bleiben auf deinem Gerät und werden nirgends hochgeladen.

---

## Funktionen

| | |
|---|---|
| **Musik** | MP3 oder WAV laden. BPM und Beats werden automatisch erkannt. |
| **Intro** *(optional)* | Ein Video aus der Fotomediathek oder aus Dateien. Es läuft stumm am Anfang, die Musik spielt darunter. |
| **Clips & Fotos** | Mehrere Videos und Bilder auf einmal auswählen und einzeln wieder entfernen. |
| **Format** | 16:9 (quer), 9:16 (hoch) oder Short (9:16, 58 s mit Fade-Out) |
| **Qualität** | 720p oder 1080p |
| **Schnitt** | Sanft 3,5 s · Langsam 2,2 s · Normal 1,7 s · Schnell 0,95 s · Random |
| **Titel** *(optional)* | Wird unten links eingeblendet und aus dem Dateinamen übernommen. Er lässt sich bearbeiten. |
| **Speichern** | „In Fotos sichern“ (Teilen-Menü) oder „Als Datei speichern“ |

Die Auswahl der Clips folgt denselben Regeln wie am Desktop:
- kein Clip zweimal direkt hintereinander
- höchstens 2 Fotos am Stück
- Fotos erst ab 2 Sekunden Länge
- Titel und Beat-Schnitte beginnen erst nach dem Intro
- Beim Short werden Intro und Outro weggelassen.

---

## So geht's

1. **Musik** wählen
2. optional ein **Intro** wählen
3. **Clips & Fotos** hinzufügen
4. **Format**, **Qualität** und **Schnitt** einstellen
5. optional den **Titel** einschalten
6. **▶ Render** antippen
7. Vorschau ansehen und **speichern**

> **Wichtig:** Gerendert wird in Echtzeit, ein 3-Minuten-Song braucht also etwa 3 Minuten.
> Lass den Bildschirm währenddessen an und bleib in der App. Sonst kann das Bild an dieser Stelle stocken.

Gefällt dir die Reihenfolge der Clips nicht, tippst du auf **„Nochmal rendern“** und bekommst eine neue Zufallsfolge.

---

## Als App auf dem Home-Bildschirm

**iPhone (Safari):** Teilen → *Zum Home-Bildschirm*
**Android (Chrome):** Menü ⋮ → *Zum Startbildschirm hinzufügen*

MVG Mobil startet dann mit eigenem Icon und ohne Adressleiste, wie eine normale App.

---

## Speichern in der Fotomediathek (iPhone)

1. Nach dem Rendern auf **„In Fotos sichern“** tippen.
2. Im Teilen-Menü **„Video sichern“** wählen.

Das funktioniert nur über eine `https://`-Adresse, deshalb liegt die App auf GitHub Pages.

---

## Browser & Ausgabeformat

| Gerät | Empfehlung | Ergebnis |
|---|---|---|
| iPhone / iPad | Safari | MP4 |
| Android | Chrome | MP4 (ältere Geräte: WebM) |
| PC | Chrome oder Edge | MP4 |

---

## Unterschiede zum Desktop-MVG

Die Mobilversion ist bewusst schlank gehalten. **Nicht** enthalten sind:
- Outro
- interner Clip-Pool mit Stimmungen
- Timeline- bzw. Clip-Editor
- mehrere Formate in einem Durchgang

Für diese Funktionen gibt es den Desktop-MVG (Windows) in der **Don Miguel de Cabarete Studio Suite**.

---

## Update

Neue Version: die neue `index.html` hochladen, die alte wird ersetzt.
Wenn das Icon auf dem Home-Bildschirm nicht wechselt: das Icon löschen und neu hinzufügen.

---

© Don Miguel de Cabarete · Ruhrgebiet × Caribe
