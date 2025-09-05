# XOR-Netz-Einführung-in-die-Bildverarbeitung-OCT

Dieses Repository bündelt zwei Notebooks (Aufgabe 1 & 2) und das offizielle Aufgabenblatt:

- **Aufgabe 1:** Minimalistisches **PyTorch-Netz** zur Lösung des **XOR-Problems** (2 Eingaben, 2 Ausgänge).  
- **Aufgabe 2:** **OCT-Bildverarbeitung**: Schwellenwertsegmentierung der Retina, **DICE-Score**-Optimierung via Morphologie, Volumenberechnung; einfache **Augmentationen** (Normalize, Flip, Shift, Center-Crop).  
Alle organisatorischen Details (Colab, GPU, Abgabetermin, Dateibenennung) siehe PDF.


## How to run
- Colab öffnen und GPU aktivieren: Laufzeit → Laufzeittyp ändern → Hardwarebeschleuniger: GPU. 
- Notebook ausführen:
- Für Aufgabe 1: Trainingsdauer protokollieren (CPU vs. GPU), Accuracy/Verlauf plotten.
- Für Aufgabe 2: Schwellenwert-Sweep, Morphologie-Vergleich, DICE-/Volumen-Berechnung und Cameraman-Augmentationen dokumentieren
