# CLAUDE.md — Website Stephan Meissner

## Projekt-Status
Die Website ist **fertig und live** auf GitHub Pages (stephan-meissner.com). Single-Page HTML/CSS/JS, deployed über GitHub Pages. Aktueller Fokus: **Design-Verfeinerung** — das cleane Layout soll subtile Tape-Art-Elemente bekommen, die es einzigartig machen.

## Über den Künstler
- Stephan Meissner, geb. 1989 in Bonn, lebt seit 2009 in Berlin
- Medium: Tape Art (Klebeband, Klebematerialien)
- Stil: Abstraktion, gerade Linien, harte Kontraste, raumfüllende Installationen
- Wurzeln: Graffiti Stylewriting → Typografie → abstrakte Tape Art
- Gründer: Tape That Collective (2011), Tape Art Convention (seit 2016), Tape Art Academy (seit 2017)
- E-Mail: sm@tapethatcollective.com
- Instagram: @stephanmeissner.artist

## Artist Statement
"Stephan Meissner has been living and working as a visual artist in Berlin since 2009. Born in Bonn in 1989, he discovered his artistic calling through classical graffiti stylewriting. His interest in letters and typography led him to explore the tension between adhering to and breaking the rules that define visual language. His focus on abstraction, characterized by straight lines and sharp contrasts, is closely linked to his use of tape and other adhesive materials as his primary medium. Through his work, Meissner invites viewers to question conventions and norms, encouraging them to either challenge or follow these rules based on their own interpretations."

## Tech Stack
- Vanilla HTML, CSS, JavaScript — kein Framework
- Alles in einer `index.html` (eingebettetes CSS + JS)
- Gehostet auf GitHub Pages
- Google Fonts (Outfit + DM Sans)
- Bilder in `images-optimized/` als WebP + JPG-Fallback

## Dateistruktur
```
├── CLAUDE.md           ← diese Datei
├── index.html          ← Hauptseite (alles drin: HTML, CSS, JS)
├── impressum.html      ← Impressum (rechtlich)
├── datenschutz.html    ← Datenschutzerklärung (rechtlich)
├── robots.txt          ← SEO
├── sitemap.xml         ← SEO
├── CNAME               ← Custom Domain für GitHub Pages
├── .gitignore
├── images-optimized/   ← Alle verwendeten Bilder (WebP + JPG)
│   ├── hero/           ← Hero-Slideshow (13 Bilder, 2560px breit)
│   ├── portfolio/      ← Portfolio nach Projekten sortiert
│   ├── about/          ← Portrait
│   └── shop/           ← Shop-Bilder
└── images/             ← Originale (gitignored, nur lokal)
```

## Seitenstruktur (Single Page)
1. **Hero** – Fullscreen-Slideshow, Name "STEPHAN MEISSNER", Untertitel "Visual Artist · Berlin"
2. **Works** – Portfolio-Grid mit Lightbox-Carousel (8 Featured + Show More)
3. **About** – Portrait + Bio + Timeline (Collective, Convention, Academy) + ausklappbare Vita
4. **Shop** – 3 Artworks, "Inquire" per mailto
5. **Contact** – Formular (mailto), Email, Instagram, Standort
6. **Footer** – Copyright, Impressum, Datenschutz, Social Icons

## Zweisprachigkeit
- DE/EN Toggle in der Navigation
- Alle Texte über `data-en` / `data-de` Attribute
- Standard: Englisch

## Design-Grundsätze
- **Neutral & clean** — Schwarz, Weiß, Grautöne. Die Kunst bringt die Farbe.
- **Galerie-Ansatz** — Die Artwork-Fotos stehen im Vordergrund
- **Typografie**: Outfit (Headings), DM Sans (Body) — kantig aber dezent
- **Animationen**: Subtil, smooth, nicht überladen
- **Kein KI-Standarddesign** — muss sich anfühlen wie von einem Designer gemacht

## Nächster Schritt: Tape-Art Design-Elemente
Das aktuelle Design ist bewusst sehr clean. Als nächstes sollen **subtile Tape-Art-Elemente** eingebaut werden, die die Website visuell an Stephans Kunstform anbinden. Ideen:
- Tape-Schnipsel / Streifen als dekorative Elemente (CSS, kein Bild)
- Diagonale Linien oder geometrische Akzente die an Tape-Streifen erinnern
- Section-Trenner die aussehen wie abgerissenes Tape
- Hover-Effekte die an Tape-Texturen erinnern
- **Wichtig**: Dezent und geschmackvoll, nicht kitschig. Die Elemente sollen die Ästhetik unterstreichen, nicht überladen.

## Qualitätskriterien
- Sieht die Seite aus wie eine professionelle Künstler-Website oder wie ein Template?
- Steht die Kunst im Vordergrund?
- Funktioniert die Navigation intuitiv?
- Ist die Seite responsive (Desktop + Mobile)?
- Funktioniert der DE/EN Toggle?
- Laden die Bilder schnell genug?

## Regeln
- Immer die bestehende `index.html` editieren, keine neuen Dateien anlegen (außer wenn nötig)
- Vor Änderungen den aktuellen Code lesen
- Keine unnötigen Dependencies oder Frameworks einführen
- Lieber weniger aber dafür impactvoll
- Die Website repräsentiert einen Künstler — sie darf Charakter haben
