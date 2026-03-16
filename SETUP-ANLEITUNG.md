# Setup-Anleitung: Ordner vorbereiten für Claude Code

## Schritt 1: Projektordner erstellen

Erstelle folgenden Ordner irgendwo auf deinem Computer (z.B. auf dem Desktop):

```
website-stephan/
```

## Schritt 2: Unterordner anlegen

Erstelle innerhalb von `website-stephan/` diese Ordner:

```
website-stephan/
├── images/
│   ├── portfolio/
│   ├── about/
│   ├── shop/
│   └── hero/
└── reference/
```

Auf Mac im Terminal geht das so:
```bash
mkdir -p ~/Desktop/website-stephan/images/{portfolio,about,shop,hero}
mkdir -p ~/Desktop/website-stephan/reference
```

## Schritt 3: CLAUDE.md reinkopieren

Kopiere die Datei `CLAUDE.md` (die du von mir bekommen hast) direkt in den Hauptordner:

```
website-stephan/
├── CLAUDE.md    ← hierhin
├── images/
│   └── ...
└── reference/
```

## Schritt 4: Bilder einsortieren

### images/portfolio/ (WICHTIG — das Herzstück)
Hier kommen deine **10-20 besten Artwork-Fotos** rein. Tipps:
- Möglichst hochauflösend (mindestens 1500px breit)
- Verschiedene Arbeiten: Installationen, Leinwände, Detailaufnahmen, Raumansichten
- Gute Beleuchtung, keine unscharfen Handyfotos
- Benenne sie beschreibend, z.B.:
  - `installation-taipei-2022.jpg`
  - `canvas-abstract-blue-2024.jpg`
  - `mural-berlin-studio-2023.jpg`
  - `detail-tape-lines-closeup.jpg`

### images/about/
- **1-2 gute Portrait-Fotos** von dir
- Am besten bei der Arbeit oder vor einem deiner Werke
- Hochformat funktioniert gut
- z.B. `portrait-studio.jpg` oder `stephan-working.jpg`

### images/shop/
- Fotos der Werke, die du **verkaufen möchtest**
- Pro Werk: 1 gutes Foto (frontal, gute Beleuchtung)
- Benenne sie so, dass man sie zuordnen kann:
  - `artwork-untitled-01-80x60.jpg`
  - `artwork-composition-02-100x80.jpg`

### images/hero/  (optional)
- Falls du ein besonders starkes Bild hast, das als Vollbild-Hero funktioniert
- Muss im Querformat sein und in hoher Auflösung (mindestens 1920px breit)
- Alternativ kann Claude Code auch eines der Portfolio-Bilder verwenden

## Schritt 5: Referenz-Screenshots

Mache Screenshots der folgenden vier Websites und speichere sie in `reference/`:

1. Öffne https://www.mediumagency.de/ → Screenshot → speichern als `mediumagency.png`
2. Öffne https://www.felipepantone.com/ → Screenshot → speichern als `felipepantone.png`
3. Öffne https://www.pichiavo.com/ → Screenshot → speichern als `pichiavo.png`
4. Öffne https://www.kai-semor.com/home-en.html → Screenshot → speichern als `kai-semor.png`

**Tipp:** Mach auch Screenshots wenn du runterscrollst, damit Claude Code mehr vom Design sieht. Z.B.:
- `mediumagency-scroll1.png`
- `pichiavo-scroll1.png`

**Du brauchst KEINEN Code von diesen Seiten zu kopieren!** Die Screenshots reichen völlig — Claude Code kann daraus den Stil ableiten.

## Schritt 6: Claude Code starten

1. Öffne dein Terminal
2. Navigiere in den Ordner:
   ```bash
   cd ~/Desktop/website-stephan
   ```
3. Starte Claude Code:
   ```bash
   claude
   ```
4. Claude Code liest automatisch die `CLAUDE.md` — das ist dein Projekt-Briefing

## Schritt 7: Ersten Prompt eingeben

Kopiere den Prompt aus der Datei `ERSTER-PROMPT.md` und füge ihn in Claude Code ein.

---

## Checkliste vor dem Start

- [ ] Ordner `website-stephan/` erstellt
- [ ] Unterordner `images/portfolio/`, `images/about/`, `images/shop/`, `images/hero/` erstellt
- [ ] Unterordner `reference/` erstellt
- [ ] `CLAUDE.md` in den Hauptordner kopiert
- [ ] 10-20 Artwork-Fotos in `images/portfolio/` gelegt
- [ ] 1-2 Portrait-Fotos in `images/about/` gelegt
- [ ] Shop-Fotos in `images/shop/` gelegt (falls schon vorhanden)
- [ ] 4+ Referenz-Screenshots in `reference/` gespeichert
- [ ] Claude Code im Ordner gestartet
