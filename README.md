# vegas LaTeX Style & Template

A personal LaTeX style and template for everyday use — lightweight, consistent, and highly readable.

This repository contains my custom `.sty` configuration (`vegas.sty`) and a sample `template.tex` designed for clean, professional document typesetting.  
It aims to provide a well-structured and optimized setup for reports, papers, or notes.

---

## 🌟 Features

### 1. Page Layout
- Uses `geometry` for precise A4 layout control.
- Optimized margins and column spacing for readability.

### 2. Encoding & Fonts
- UTF-8 input and T1 font encoding.
- Times family font via `mathptmx` and `pslatex`.
- `microtype` for subtle typographic improvements.

### 3. Mathematics
- AMS math packages (`amsmath`, `amssymb`, `amsfonts`).
- Bold math support via `bm`.
- SI units and number formatting with `siunitx`.

### 4. Figures & Colors
- Full `graphicx` and `xcolor` support.
- Unified caption style (bold label, normal text).
- Subfigures via `subcaption`.

### 5. Tables
- Professional-quality tables with `booktabs`.
- Multirow, longtable, and CSV import capabilities.

### 6. Algorithms
- `algorithm2e` with ruled and numbered lines.

### 7. Formatting & Typography
- Fine-grained control over sections (`titlesec`).
- Custom `\maketitle` handling with `titling`.
- Balanced last-page columns and improved float behavior.

### 8. References & Hyperlinks
- `hyperref` with color links and backreferences.
- Custom `autoref` names and consistent hyperlink colors.

### 9. Highlighting & Comments
- Highlight commands (`\hlcyan`, `\hlyellow`, `\hlgreen`, `\hlgrey`).
- Commenting and markup with `pdfcomment`.
- Toggle comment visibility with `\showcommentstrue` / `\showcommentsfalse`.

---

## 🧩 Usage

Include the style file in your LaTeX document:

For English:
```latex
\usepackage{vegas}
```

For Chinese:
\usepackage{vegaszh}
