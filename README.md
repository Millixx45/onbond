# onbond

Eine einfache Landing Page für das **onbond**-Projekt.

---

## Landing Page anzeigen – Schritt-für-Schritt-Anleitung

### Voraussetzungen

- Git installiert
- Ein moderner Webbrowser (Chrome, Firefox, Edge, Safari)

---

### Option A – Direkt im Browser öffnen (kein Server nötig)

1. **Repository klonen**
   ```bash
   git clone https://github.com/Millixx45/onbond.git
   cd onbond
   ```

2. **Auf den richtigen Branch wechseln**
   ```bash
   git checkout claude/landing-page-guide-D2nMx
   ```

3. **Datei im Browser öffnen**

   - **Windows:** Doppelklick auf `index.html` im Explorer
     oder im Terminal:
     ```bash
     start index.html
     ```
   - **macOS:**
     ```bash
     open index.html
     ```
   - **Linux:**
     ```bash
     xdg-open index.html
     ```

   Die Landing Page öffnet sich direkt in deinem Standardbrowser.

---

### Option B – Lokalen Entwicklungsserver starten (empfohlen)

Ein lokaler Server verhindert Probleme mit Browser-Sicherheitsrichtlinien
(z. B. beim späteren Laden von API-Daten).

#### Mit Python (kein zusätzliches Tool nötig)

```bash
# Python 3
python3 -m http.server 8080

# Python 2 (falls noch installiert)
python -m SimpleHTTPServer 8080
```

Dann im Browser aufrufen: [http://localhost:8080](http://localhost:8080)

#### Mit Node.js / npx

```bash
npx serve .
```

Dann im Browser aufrufen: [http://localhost:3000](http://localhost:3000)

#### Mit VS Code Live Server

1. Extension **Live Server** installieren (Ritwick Dey)
2. Rechtsklick auf `index.html` → **"Open with Live Server"**
3. Browser öffnet automatisch `http://127.0.0.1:5500`

---

### Ergebnis

Du siehst die onbond Landing Page mit:

- **Header** mit Navigation
- **Hero-Bereich** mit Headline und Call-to-Action
- **Feature-Karten** (Echtzeit-Daten, Sicherheit, Abwicklung, Märkte)
- **CTA-Band** zur Registrierung
- **Footer**

---

## Projektstruktur

```
onbond/
├── index.html   ← Landing Page (HTML + CSS in einer Datei)
└── README.md    ← Diese Anleitung
```
