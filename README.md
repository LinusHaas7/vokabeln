# Vokabelkiste

Eine einfache App zum Lernen von Vokabeln (Englisch–Deutsch). Du lädst ein Foto deiner Liste hoch und lernst die Wörter danach mit Karteikarten.

- Die Fotos werden **direkt im Browser** gelesen, mit [Tesseract.js](https://github.com/naptha/tesseract.js). Sie werden nirgendwo hochgeladen.
- Die App kostet nichts und braucht kein Konto und keinen Server.
- Die Vokabeln werden im Browser des jeweiligen Geräts gespeichert.

## Online stellen mit GitHub Pages

1. Lade `index.html` in ein GitHub-Repository hoch. Das Repository muss **öffentlich** sein, wenn du ein kostenloses Konto hast.
2. Gehe im Repository auf **Settings → Pages**.
3. Wähle bei „Branch“ **main** und den Ordner **/ (root)** aus und klicke auf **Save**.
4. Nach etwa einer Minute ist die App erreichbar unter
   `https://DEIN-NAME.github.io/REPO-NAME/ (diese App: https://linushaas7.github.io/vokabeln/)`

Diesen Link kannst du an alle weitergeben.

## Gut zu wissen

- Beim ersten Foto lädt die App einmalig die Texterkennung (etwa 10–20 MB). Danach geht es schneller.
- Am besten klappen gedruckte Listen und Screenshots. Handschrift wird oft nicht erkannt.
- Die Vokabeln gibt es nur auf dem Gerät und in dem Browser, mit dem man gelernt hat. Wer die Browserdaten löscht, verliert sie.
