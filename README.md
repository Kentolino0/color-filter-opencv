# 🎨 Echtzeit-Farbfilter mit OpenCV (Python)

Ein einfaches Projekt zur Farberkennung mit Hilfe von OpenCV und HSV-Filterung. Über sogenannte **Trackbars** kann man interaktiv den Farbbereich (Hue, Saturation, Value) anpassen und in Echtzeit die Maskierung und Filterung im Bild beobachten.

---

## 📸 Vorschau

Das Programm zeigt in mehreren Fenstern:
- Das Originalbild
- Das Bild in HSV-Farbraum
- Die Farbmaske
- Das Ergebnis (nur ausgewählte Farbe sichtbar)
- Einen Stack aller Bilder in einem einzigen Fenster

---

## 🧰 Verwendete Technologien

- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)

---

## ▶️ Ausführung

1. Stelle sicher, dass du `opencv-python` und `numpy` installiert hast:
   ```bash
   pip install opencv-python numpy
