# CLAUDE.md — Website Stephan Meissner

## Projektübersicht
Persönliche Künstler-Website für Stephan Meissner, Tape Art Artist aus Berlin. Eigenständige HTML/CSS/JS Website ohne Framework. Muss auf eigenem Hosting funktionieren (aktuell auf Wix unter www.stephan-meissner.com).

## Über den Künstler
- Stephan Meissner, geb. 1989 in Bonn, lebt seit 2009 in Berlin
- Medium: Tape Art (Klebeband, Klebematerialien)
- Stil: Abstraktion, gerade Linien, harte Kontraste, raumfüllende Installationen
- Wurzeln: Graffiti Stylewriting → Typografie → abstrakte Tape Art
- Gründer: Tape That Collective (2011), Tape Art Convention (seit 2016), Tape Art Academy (seit 2017)
- Philosophie: Konventionen hinterfragen, bewusst Regeln brechen oder befolgen
- E-Mail: sm@tapethatcollective.com
- Instagram: @stephanmeissner.artist
- Collective: tapethatcollective.com

## Artist Statement
"Stephan Meissner has been living and working as a visual artist in Berlin since 2009. Born in Bonn in 1989, he discovered his artistic calling through classical graffiti stylewriting. His interest in letters and typography led him to explore the tension between adhering to and breaking the rules that define visual language. His focus on abstraction, characterized by straight lines and sharp contrasts, is closely linked to his use of tape and other adhesive materials as his primary medium. Through his work, Meissner invites viewers to question conventions and norms, encouraging them to either challenge or follow these rules based on their own interpretations. This process of questioning, rethinking, and sometimes overturning norms is reflected in every taped line, shaping the appearance and meaning of his artworks."

## Tech Stack
- Vanilla HTML, CSS, JavaScript (kein Framework)
- Muss standalone funktionieren (einfach Ordner auf Webserver hochladen)
- Google Fonts über CDN
- Responsive Design (Mobile-First)
- Lazy Loading für Bilder
- SEO-Grundlagen (Meta-Tags, Open Graph, semantisches HTML)

## Ordnerstruktur
```
website-stephan/
├── CLAUDE.md              ← diese Datei
├── index.html             ← Hauptseite
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   ├── portfolio/         ← Artwork-Fotos, nach Projekten sortiert (siehe unten)
│   ├── about/             ← Portrait-Foto(s)
│   ├── shop/              ← Fotos der verkäuflichen Werke (7 Bilder)
│   └── hero/              ← Hero-Bereich Bilder (optional)
├── reference/             ← Screenshots von Referenz-Websites (nicht deployen)
│   ├── mediumagency.png
│   ├── felipepantone.png
│   ├── pichiavo.png
│   └── kai-semor.png
└── fonts/                 ← Falls lokale Fonts gewünscht
```

## Portfolio-Projekte (in `images/portfolio/`)
Die Bilder sind nach Projekten in Unterordner sortiert. Das erste Bild pro Ordner kann als Hauptbild in der Galerie dienen, die anderen als Detailansichten. Hier die vollständige Übersicht:

| Ordner | Projekt | Beschreibung | Bilder |
|--------|---------|-------------|--------|
| `00-material-and-process` | Material & Prozess | Tape-Rollen, bei der Arbeit | 3 |
| `01-fip-rauminstallation` | FiP Rauminstallation | Große orange/blaue Installation mit Säulen, Streifen-Muster | 3 |
| `02-illuseum-grid-room` | Illuseum Grid Room | Schwarz-weiß Gitter-Raum, immersiv, AR-Element | 4 |
| `03-taiwan-exhibition` | Taiwan Exhibition | Riesige bunte Halle (blau/gelb/braun), Songshan Cultural Park, Zug | 8 |
| `04-artcarden-installation` | Artcarden Installation | Explosiv bunt, raumfüllend, alle Farben | 2 |
| `05-sleek-cadillac` | Sleek × Cadillac | Schwarz-weiß Tape-Streifen auf Auto, Prozess + Ergebnis | 3 |
| `06-weshare-artcar` | WeShare Art Car | Bunter VW vor Graffiti-Wand | 1 |
| `07-kuwait-car` | Kuwait Car Detail | Bunte geometrische Formen, Nahaufnahme mit Neonlicht | 1 |
| `08-porsche-artcar` | Porsche Art Car | Bunter Porsche 911 vor passender Wand, Studio-Setting | 1 |
| `09-moebius-galerie` | Möbius | Farbige Diagonalstreifen auf Glas in Galerie + Dreieck-Installation | 2 |
| `10-game-over-sweetspot` | Game Over / Sweetspot | Raum-Installationen mit Text, Spiegel, bunte Streifen/Kreise | 3 |
| `11-roland-berger` | Roland Berger | Corporate Mural, Prozessbild bei der Arbeit | 3 |
| `12-popcorn-hongkong` | Popcorn Hong Kong | Weiße Wände in Shopping Mall, Treppenhaus | 5 |
| `13-mt-factory-tour-japan` | MT Factory Tour Japan | Kamera-Viewfinder auf bunten Raum, Japan 2018 | 2 |
| `14-berlin-mural` | Berlin Mural | Großes Wandbild in Berlin | 2 |
| `15-tape-art-convention` | Tape Art Convention | Decken-Installation, wild/explosiv, mit Leinwänden | 1 |
| `16-festival-of-lights` | Festival of Lights | Großes Mural von oben, bunte Tape-Streifen auf Betonwand | 1 |
| `17-tape-art-around-the-world` | Tape Art Around The World | "I ♥ NY" Mural (USA) + Guatemala City | 2 |
| `18-zukunftsmusik-cyberport` | Zukunftsmusik / Cyberport | Bunte Streifen auf Gebäudefassade, perspektivisch | 2 |
| `19-japanisches-palais` | Japanisches Palais Dresden | Buntes Mural in historischem Treppenhaus | 1 |
| `20-trade-desk` | Trade Desk | Corporate Installation, buntes Glasfenster mit Portrait | 3 |
| `21-tape-that-space` | Tape That Space | Rauminstallation mit Personen, bunt, 3D-Effekte | 5 |
| `22-freiraum-bw` | Freiraum (s/w) | Schwarz-weiße Wandarbeit, geometrisch, Prozess | 4 |
| `23-rsa-grid-room` | RSA Grid Room | Schwarz-weißer Gitter-Raum, komplett immersiv | 1 |
| `25-parkhaus-mural` | Parkhaus Mural | Lila/cyan/gelb Abstraktion im Parkhaus | 3 |
| `26-bvg-pride-ubahn` | BVG Pride U-Bahn | Regenbogen-Tape in Berliner U-Bahn-Stationen | 4 |
| `27-formula-e-artcar` | Formula E Art Car | Blauer Tape-Art-Rennwagen in Backsteingebäude | 1 |
| `28-corridor-installation` | Korridor-Installation | Minimalistische schwarze Tape-Linien im weißen Flur | 1 |
| `29-corporate-bw-installation` | Corporate s/w Installation | Schwarz-weiße Streifen-Muster an Wand/Decke mit Skulptur | 2 |
| `30-studio-murals` | Studio Murals | Eigenständige bunte Wandarbeiten im Studio | 2 |

**Hinweis:** `images/about/` enthält ein Portrait-Foto. `images/shop/` enthält 7 Artwork-Fotos für den Shop. `images/hero/` enthält ein Hero-Bild. `images/portfolio/31-raw-unprocessed/` enthält DNG-Rohdateien die noch nicht verwendet werden.

## Seitenstruktur
Single-Page-Website mit folgenden Sektionen:

1. **Hero** – Fullscreen-Einstieg, Name "STEPHAN MEISSNER", Untertitel "Tape Art · Visual Artist · Berlin"
2. **Portfolio / Works** – Galerie der besten Arbeiten (Bilder aus `images/portfolio/`)
3. **About** – Portrait + Bio + Stats (15+ Jahre, 40+ Länder, Gründung 2011)
4. **Projects** – Tape That Collective, Tape Art Convention, Tape Art Academy
5. **Shop** – Original-Artworks zum Verkauf (vorerst "Price on request" + Anfrage per Mail)
6. **Contact** – Formular (mailto:), Email, Instagram, Standort Berlin

## Zweisprachigkeit
- Komplette Website in Deutsch UND Englisch
- Language-Toggle (DE/EN) in der Navigation
- Alle Texte in beiden Sprachen (z.B. über data-Attribute oder JSON-basiertes i18n)
- Standard-Sprache: Englisch

## Design-Richtung

### Referenz-Websites (Screenshots ggf. in `/reference/`)
Orientiere dich an einer Mischung aus diesen vier Seiten. Hier detaillierte Beschreibungen:

#### 1. mediumagency.de — "Der kraftvolle Auftritt"
- **Hero:** Schwarzer Hintergrund, riesige weiße Bold-Typo ("ENGAGE"), darunter Video das automatisch abspielt. Text animiert (Blur-Effekt). Subline "ACTIVATING BRANDS THROUGH VISUAL ART AND CULTURE"
- **Navigation:** Oben horizontal, weiß auf schwarz, großgeschrieben (PROJECTS, SERVICES, CONTACT, ABOUT), Social Icons rechts. Ein blauer Akzent-Block als Designelement
- **Farben:** Schwarz (#000), Weiß, ein kräftiger Blau-Akzent
- **Typografie:** Sehr bold, groß, Sans-Serif, selbstbewusst
- **Was übernehmen:** Den kraftvollen ersten Eindruck, die dunkle Ästhetik, die mutige Typografie

#### 2. felipepantone.com — "Die Galerie"
- **Hero:** Komplett weiß/hell, nur Name oben links "FELIPE PANTONE" in Bold Sans-Serif, daneben "WORK" und "FP"
- **Layout:** Extrem reduziert — fast nur große Artwork-Fotos auf weißem Hintergrund, ein Bild links, asymmetrisch platziert, viel leerer Raum
- **Navigation:** Minimal, oben links, nur 2-3 Punkte
- **Farben:** Fast nur Weiß, die Kunst bringt alle Farbe
- **Was übernehmen:** Die Reduktion, die Kunst steht absolut im Vordergrund, Galerie-Feeling, viel Whitespace

#### 3. pichiavo.com — "Das Immersive"
- **Hero:** FULLSCREEN, 4-5 vertikale Bildstreifen/Panels die verschiedene Artworks nebeneinander zeigen, darüber riesige weiße Serif-Typografie ("UrbanMythology") die ÜBER den Bildern liegt
- **Navigation:** Logo oben links ("PichiAvo" in Handschrift), "MENU" und "CART" oben rechts
- **Farben:** Die Bilder dominieren alles, kräftige Farben in den Artworks, Website selbst neutral
- **Typografie:** Elegante große Serif (Italic) für Headlines, kontrastiert mit den Streetart-Bildern
- **Was übernehmen:** Die Bildstreifen-Idee im Hero, Typografie über Bildern, immersives Gefühl, theatralische Inszenierung

#### 4. kai-semor.com — "Der Clean Artist"
- **Layout:** Sidebar-Navigation LINKS (Home, About, Works, Available Artwork, Contact), Content rechts
- **Hero:** Großes Foto rechts neben der Navigation, darunter Projekt-Titel mit Datum und orangener Linie
- **Navigation:** Sauber, vertikal, großgeschrieben, DE/EN Toggle oben rechts
- **Farben:** Sehr hell/weiß, ein starker orangener/roter Akzent-Punkt und Akzent-Linien
- **Typografie:** Clean Sans-Serif, Bold für Projekt-Titel, leicht und lesbar für Beschreibungen
- **Was übernehmen:** Die saubere Navigation, den DE/EN Toggle, den einzelnen Farbakzent, chronologische Projektdarstellung

### Stil
- Professionell aber mit Charakter — KEIN generisches Template
- Die Kunst muss im Vordergrund stehen (Galerie-Ansatz)
- Immersiver, experimenteller Touch im Hero
- Clean, intuitive Navigation mit DE/EN Toggle
- **Formensprache aus den Artworks ins Layout übertragen**: Klare Linien, diagonale Schnitte, dynamische Kontraste, geometrische Präzision — das Layout selbst soll sich wie Tape Art anfühlen
- Raumgefühl/Perspektive-Effekte (Stephan arbeitet oft raumfüllend)
- Animationen: smooth, subtil, nicht überladen

### Farben
- **REIN NEUTRAL** — keine Akzentfarbe in den Vordergrund stellen
- Schwarz (#0a0a0a), Warmweiß (#f0ede8), Abstufungen von Grau
- Die Kunst selbst bringt ALLE Farbe — die Website ist die stille Bühne
- Hover-States, Linien, Divider: nur Weiß/Grau-Abstufungen

### Typografie
- Modern, kantig aber **dezent** — nicht "Superbowl"-mäßig fett
- Überschriften: Syne, Medium/Semibold (NICHT 800/Extra-Bold im Hero)
- Fließtext: Space Grotesk oder Inter
- **Name im Hero: elegant und zurückhaltend** — eher wie eine Galerie-Beschriftung, nicht wie ein Plakat
- Größenverhältnisse: Name angemessen groß aber nicht bildschirmfüllend

## Shop-Bereich
- Vorerst einfach: Produktkarten mit Bild, Titel, Medium/Größe, "Price on request"
- Anfrage-Button verlinkt auf mailto:sm@tapethatcollective.com
- Stripe-Integration kommt später
- Platz für ein Artbook vormerken (kommt noch nicht rein)

## Workflow-Hinweise

### Puppeteer Screenshot Loop
Nach jeder größeren Änderung:
1. Screenshot der Website machen (Desktop + Mobile)
2. Visuell prüfen
3. Verbesserungen identifizieren und umsetzen
4. Wiederholen bis das Ergebnis hochwertig ist

### Qualitätskriterien
- Sieht die Seite aus wie eine professionelle Künstler-Website oder wie ein Template?
- Steht die Kunst im Vordergrund?
- Funktioniert die Navigation intuitiv?
- Sind die Animationen smooth und nicht störend?
- Ist die Seite responsive und performant?
- Funktioniert der DE/EN Toggle korrekt?

## Wichtig
- Schau dir ZUERST die Bilder in `images/` und die Referenz-Screenshots in `reference/` an, bevor du mit dem Code anfängst
- Lieber weniger Inhalt aber dafür impactvoll
- Die Website repräsentiert einen Künstler, keinen Konzern — sie darf Charakter haben
- Kein KI-Standarddesign — das Ergebnis soll sich anfühlen, als hätte ein Designer es gemacht
