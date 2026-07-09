# 🏟 Retro Football Tales

> A vintage newspaper-style football blog covering the beautiful game's greatest stories, moments, and legends — from the 1950s to the 2000s.

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-HuggingFace%20Spaces-orange?style=for-the-badge)](https://bharatsinghbisht-retro-football-tales.hf.space)
[![HTML](https://img.shields.io/badge/Single%20File-HTML-blue?style=for-the-badge)](index.html)
[![No API](https://img.shields.io/badge/No%20API%20Key-100%25%20Free-green?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

---

## ⚽ Features

### 📰 Stories
8 full-length feature articles written in classic broadsheet style, covering football's most defining moments across six decades. Cycles through stories on demand.

- Brazil's Perfect Summer — Mexico 1970
- The Hand of God — Maradona vs England, 1986
- Two Minutes From Defeat — Man United 1999
- Total Football — Cruyff's Netherlands, 1974
- The Miracle of Istanbul — Liverpool 2005
- The Match That Shattered English Certainty — Hungary 1953
- The Lisbon Lions — Celtic's European Conquest, 1967
- Zidane's Two Headers — France World Cup 1998

### 🖼 Gallery
12 iconic moments from across the decades, filterable by era (1950s–2000s). Each moment captured with atmospheric visuals and contextual captions.

### 📊 Legends
12 legendary player cards with full career stats, honours, club history, biography, and legacy quotes. Searchable by name, club, or nation. Filterable by position.

**Legends featured:** Pelé · Johan Cruyff · Diego Maradona · Franz Beckenbauer · Zinedine Zidane · Ronaldo Nazário · Ronaldinho · Paolo Maldini · Lev Yashin · Michel Platini · George Best · Eusébio

---

## 🎨 Design

Mixed-era visual identity combining energy from across football's greatest decades:

| Element | Choice | Reason |
|:---|:---|:---|
| Display font | Bebas Neue | Matchday programme / stadium scoreboard energy |
| Headline font | Playfair Display | Classic broadsheet authority |
| Caption font | Special Elite | Typewriter / telegram texture |
| Palette | Midnight · Rust · Gold · Cream | Aged newspaper + retro kit colours |
| Layout | Newspaper column grid | Editorial authenticity |

---

## 🛠 Tech Stack

| Layer | Tech |
|:---|:---|
| Frontend | Vanilla HTML / CSS / JavaScript |
| Fonts | Google Fonts (Bebas Neue, Playfair Display, Special Elite, Inter) |
| Hosting | HuggingFace Static Spaces |
| API | None — fully self-contained |

**No build step. No dependencies. No API key. One file.**

---

## 🚀 Deploy

### HuggingFace Spaces (Static — recommended)
1. Create new Space → SDK: **Static**
2. Upload `index.html`
3. Live instantly at `https://YOUR_USERNAME-retro-football-tales.hf.space`

### GitHub Pages
1. Create repo → upload `index.html`
2. Settings → Pages → Deploy from main branch
3. Live at `https://YOUR_USERNAME.github.io/retro-football-tales`

### Local
```bash
# No server needed — just open in browser
open index.html
```

---

## 📁 Project Structure

```
retro-football-tales/
├── index.html    # Entire app — stories, gallery, legends, styles, scripts
└── README.md
```

---

## 🔧 Customisation

All content is stored as plain JavaScript arrays inside `index.html` — easy to edit:

- **Add a story** → append to the `STORIES` array
- **Add a gallery moment** → append to the `GALLERY` array
- **Add a player** → append to the `PLAYERS` array

No framework knowledge required.

---

## 👤 Author

**Bharat Singh Bisht**
Full Stack Developer & Scrum Master · B.Tech CSE, IILM University

[![LinkedIn](https://img.shields.io/badge/LinkedIn-bharatsinghbisht-blue?logo=linkedin)](https://linkedin.com/in/bharatsinghbisht)
[![Email](https://img.shields.io/badge/Email-bharatsinghbisht1104@gmail.com-red?logo=gmail)](mailto:bharatsinghbisht1104@gmail.com)
[![Resume Analyzer](https://img.shields.io/badge/Also%20check-AI%20Resume%20Analyzer-purple?logo=huggingface)](https://bharatsinghbisht-ai-resume-analyzer.hf.space)

---

## 📄 License

MIT — free to use, modify, and distribute.
