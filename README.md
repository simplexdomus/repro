# Repro

**Cellular Evolution & Reproduction**

---

An interactive, multi-page visualization exploring cellular biology, evolution, and the molecular machinery of life. From the first prokaryotes to the complex multicellular organisms of today.

## Pages

### Index — Evolution
The main page featuring an animated mitosis hero, evolutionary timeline, and comprehensive sections on cellular biology.

### ExtraRepro — Deep Molecular Biology
An extended deep-dive into molecular biology covering DNA structure, RNA types, protein synthesis, cell signaling, epigenetics, and more.

## Features

### Visualizations
- **Animated Mitosis** — Smooth, flowing cell division animation with all phases
- **DNA Double Helix** — Rotating 3D helix visualization
- **ATP Energy Flow** — Mitochondrial energy production animation
- **Cell Cycle Diagram** — Interactive G1, S, G2, M phase exploration

### Content Sections (Index)
1. **Introduction** — The living cell: unity, organization, reproduction
2. **Cell Types** — Prokaryotes vs. Eukaryotes comparison
3. **Evolutionary Timeline** — 4.5 billion years of cellular evolution
4. **Reproduction Strategies** — Asexual, sexual, conjugation, viral
5. **Mitosis** — Interactive phase-by-phase exploration
6. **Cellular Machinery** — 8 key organelles with facts
7. **Cellular Energy** — Glycolysis, Krebs cycle, electron transport
8. **Genetics** — DNA structure and base pairing

### Content Sections (ExtraRepro)
1. **Molecular Basis of Life** — Information, structure, energy
2. **DNA Structure** — The double helix in detail
3. **RNA World** — mRNA, tRNA, rRNA, miRNA
4. **Protein Synthesis** — Transcription and translation
5. **Cell Cycle** — G1, S, G2, M phases
6. **Cellular Machinery** — Organelles and their functions
7. **Cell Signaling** — Autocrine, paracrine, endocrine
8. **Epigenetics** — Beyond the genetic code
9. **Milestones Timeline** — Key discoveries in molecular biology
10. **Interactive Quiz** — Test your knowledge

### Interface
- Side navigation with section indicators
- Progress bar showing scroll position
- Generative ambient audio (Web Audio API)
- Smooth scroll animations and transitions
- Responsive, monochromatic design

## Technology

Pure HTML, CSS, and JavaScript. No frameworks, no libraries, no build process.

- **Canvas API** — All animations rendered in real-time
- **Web Audio API** — Generative ambient soundscape
- **IntersectionObserver** — Scroll-triggered animations
- **CSS Variables** — Consistent theming

## Live Demo

[View on GitHub Pages](https://simplexdomus.github.io/repro)

## Local Development

```bash
git clone https://github.com/simplexdomus/repro.git
cd repro
```

Open `index.html` or `extrarepro.html` in a browser.

## Structure

```
repro/
├── index.html      # Main evolution page
├── extrarepro.html # Deep molecular biology page
├── README.md       # This file
└── LICENSE         # MIT License
```

---

*A meditation on cellular life, molecular complexity, and 3.8 billion years of evolution.*
