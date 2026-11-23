# Fragment Editor

Ein einfacher Editor, um zwei Schriften in einem Wort zu kombinieren. Rahmen aufziehen: außen steht Schrift A, innen Schrift B.

**Demo:** https://clemensoso.github.io/fragment-editor/

## Bedienung

- **Rahmen (1):** Rahmen aufziehen, verschieben, an den Ecken in der Größe ändern
- **Inhalt (2):** Schrift innerhalb eines Rahmens verschieben
- **Stück (3):** Rahmen samt Inhalt verschieben
- **Freiform (4):** Rahmen anklicken und die Ecken frei verziehen, z. B. für schräge Formen
- Pfeiltasten verschieben (Shift = 10 px), ⌫ löscht, ⌘Z macht rückgängig

Export als **SVG** (Buchstaben als echte Vektorpfade, per opentype.js) oder als PNG. Oben rechts lässt sich die Oberfläche zwischen Deutsch und Englisch umschalten.

Alles steckt in einer einzigen `index.html`, ohne Build-Schritt. Die Schriften kommen von Google Fonts, für den SVG-Export werden die Schriftdateien von Fontsource (jsDelivr) geladen.
