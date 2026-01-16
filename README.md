Purebasic Module von [Hoeppner1867](https://github.com/Hoeppner1867/PureBasic/commits?author=Hoeppner1867)

Module von Hoeppner1867, die ich für eines meiner Projekte etwas angepasst habe.

ListEx

- BlendColor ist Transparent
- Absturz bei Click auf eine leere Fläche
- Fehler bei GetItemText wenn keine Spalte oder Zeile ausgewählt ist
- Bessere Unterstützung von Maus und Scrollbar
- #UseRealStringGadget erzeugt ein StringGadget() zur Eingabe
- Focus Row bei Tab und ShiftTab (noch Abschaltbar machen?)
- Add GetFingerprint() - CRC32 Fingerprint des gesamten Textes in der Tabelle
- GetItemColor()
- Add #Autoclose - Muss bei ListEx::Gadget angegeben werden damit beim Event #PB_Event_CloseWindow automatisch das Gadget (Daten) gelöscht werden
- Add FreeListExGadget() - Gibt das Gadget und wenn Angegeben das Canvas frei
- Bug? CalcScrollRange_() Scrollbar wird nicht mehr auf 0 zurückgesetzt, wenn sie innerhalb des scrollbereiches liegt
- Beim Verlassen des Gadget mit der Maus wird BindShortcuts_(#False) und BindTabulator_(#False) aufgerufen. Ansonsten funktionieren Enter und Tab nicht mehr im EditorGadget.

pbPDF

- Bugfix in MultiCell()
- Add FreePDF()

===== MIT License =====

Copyright (c) 2019 Thorsten Hoeppner

Permission is hereby granted, free of charge, To any person obtaining a copy
of this software And associated documentation files (the "Software"), To deal
in the Software without restriction, including without limitation the rights
To use, copy, modify, merge, publish, distribute, sublicense, And/Or sell
copies of the Software, And To permit persons To whom the Software is
furnished To do so, subject To the following conditions:

The above copyright notice And this permission notice shall be included in all
copies Or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS Or
IMPLIED, INCLUDING BUT Not LIMITED To THE WARRANTIES OF MERCHANTABILITY,
FITNESS For A PARTICULAR PURPOSE And NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS Or COPYRIGHT HOLDERS BE LIABLE For ANY CLAIM, DAMAGES Or OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT Or OTHERWISE, ARISING FROM,
OUT OF Or IN CONNECTION With THE SOFTWARE Or THE USE Or OTHER DEALINGS IN THE
SOFTWARE.