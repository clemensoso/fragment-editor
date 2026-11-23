# Fragment Editor

Ein einfacher Editor, um mehrere Schriften in einem Wort zu kombinieren. Rahmen aufziehen: außen steht Schrift A, innen B, C … (bis zu sechs Schriften).

**Demo:** https://clemensoso.github.io/fragment-editor/

## Bedienung

- **Rahmen (1):** Rahmen aufziehen, verschieben, an den Ecken in der Größe ändern
- **Inhalt (2):** Schrift innerhalb eines Rahmens verschieben
- **Stück (3):** Rahmen samt Inhalt verschieben
- **Freiform (4):** Punkte oder ganze Kanten frei verziehen, z. B. für schräge Formen. Doppelklick auf eine Kante fügt einen Punkt hinzu, auf einen Punkt entfernt ihn
- **Zufall (R):** erzeugt eine zufällige Komposition mit kontrastierenden Schriften
- An Ecken und Kanten ziehen ändert die Größe
- ⇧ Shift: Quadrat bzw. Seitenverhältnis halten, Bewegungen gerade bzw. in 45°-Schritten
- ⌥ Alt: von der Mitte aus skalieren, ⌥-Ziehen dupliziert einen Rahmen
- ⌘D dupliziert, Pfeiltasten verschieben (Shift = 10 px), ⌫ löscht, ⌘Z macht rückgängig

Export als **SVG** (Buchstaben als echte Vektorpfade, per opentype.js) oder als PNG. Oben rechts lässt sich die Oberfläche zwischen Deutsch und Englisch umschalten.

Alles steckt in einer einzigen `index.html`, ohne Build-Schritt. Die Schriften kommen von Google Fonts, für den SVG-Export werden die Schriftdateien von Fontsource (jsDelivr) geladen.
