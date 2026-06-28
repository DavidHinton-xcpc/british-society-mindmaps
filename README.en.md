# 🇬🇧 British Society & Culture — Interactive Mind Maps

English | [中文](./README.md)

> 5 interactive mind maps covering the core knowledge of British society and culture.

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## ✨ Highlights

- **5 knowledge modules**: Geography & Culture, History (I & II), Political System, Education System, News Media
- **Bilingual terminology**: Each key term includes Chinese–English definitions, e.g. `📖 **Constitutional Monarchy（君主立宪制）**: ...`
- **Interactive experience**: Click nodes to expand/collapse, hover for term definitions, zoom and drag
- **Zero installation**: Pure HTML files — just open in a browser

## 🚀 Quick Start

### Option 1: Open HTML files directly

```bash
git clone https://github.com/DavidHinton-xcpc/british-society-mindmaps.git
# Open any file in the html/ directory
open html/英国历史.html          # macOS
xdg-open html/英国历史.html      # Linux
start html/英国历史.html          # Windows
```

### Option 2: GitHub Pages (online)

👉 [Browse all mind maps online](https://davidhinton-xcpc.github.io/british-society-mindmaps/)

## 📋 Mind Map Index

| # | Mind Map | Chapter | Key Topics |
|---|---------|---------|------------|
| 1 | [Geography & Culture](html/英国地理与文化.html) | Ch1: General Introduction | Topography, climate, population, family life, holidays |
| 2 | [British History](html/英国历史.html) | Ch2+Ch3: A Brief History I & II | Roman conquest, Norman conquest, feudalism, bourgeois revolution, Industrial Revolution, Chartism |
| 3 | [Political System](html/英国政治体制.html) | Ch4: Political System | Constitutional monarchy, separation of powers, party system |
| 4 | [Education System](html/英国教育体制.html) | Ch7: Education System | Primary, secondary, and higher education |
| 5 | [News Media](html/英国新闻媒体.html) | Ch10: News Media | The press, radio & TV, digital broadcasting, news agencies, online media |

## 🛠 Tech Stack

- **[markmap](https://markmap.js.org/)** — Markdown to interactive mind map
- **[d3.js](https://d3js.org/)** v7 — Data visualization
- **markmap-lib** + **markmap-view** v0.15.4 — Mind map rendering engine
- **Pure static HTML** — No build tools, no dependencies to install

## 📂 Project Structure

```
british-society-mindmaps/
├── html/                     # 5 interactive mind map HTML files
│   ├── 英国地理与文化.html
│   ├── 英国历史.html
│   ├── 英国政治体制.html
│   ├── 英国教育体制.html
│   └── 英国新闻媒体.html
├── src/                      # Source Markdown files (7 chapters)
│   ├── # Contents.md
│   ├── # Chapter One: General Introduction.md
│   ├── # Chapter Two: A Brief History (I).md
│   ├── # Chapter Three: A Brief History (II).md
│   ├── # Chapter Four: Political System.md
│   ├── # Chapter Seven: Education System.md
│   └── # Chapter Ten: News Media.md
├── index.html                # GitHub Pages directory page
├── README.md                 # Chinese documentation
├── README.en.md              # This file
├── DISCLAIMER.md             # Disclaimer
└── LICENSE                   # CC BY-NC-SA 4.0 license
```

## 📖 Terminology Format

Each term follows a bilingual format:

```
📖 **English Term（中文术语）**: Bilingual definition
```

Examples:
- 📖 **Constitutional Monarchy（君主立宪制）**: A system of government in which a monarch acts as head of state within the parameters of a constitution.
- 📖 **The Heptarchy（七国时代）**: The seven main Anglo-Saxon kingdoms in early medieval England.

## 📊 Data Source

Knowledge content is based on a British Society & Culture course, covering:

- Chapter 1: General Introduction (geography, culture, population, family, holidays)
- Chapter 2–3: A Brief History I & II (prehistory to Industrial Revolution)
- Chapter 4: Political System (constitutional monarchy, separation of powers, parties)
- Chapter 7: Education System (primary, secondary, higher education)
- Chapter 10: News Media (press, broadcasting, digital media)

See [`DISCLAIMER.md`](DISCLAIMER.md) for details.

## 📄 License

This project is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

- ✅ Learning, teaching, and research use
- ❌ Commercial use
- 🔄 Derivatives must use the same license

See [LICENSE](LICENSE) for the full legal text.

## 🤝 Contributing

Contributions for content corrections are welcome via Issues or Pull Requests. Please refer to [DISCLAIMER.md](DISCLAIMER.md).

## 🙏 Acknowledgements

- [markmap](https://markmap.js.org/) — Excellent Markdown mind map tool
- [d3.js](https://d3js.org/) — Powerful data visualization library