# Modern-Deedy – Photo & Dots Edition

A personal fork of the popular **modern-deedy** one-page LaTeX résumé that adds a few visual upgrades while keeping the original’s clean, single-column look.

| 🔍 At a glance | |
|---|---|
| **Base template** | [modern-deedy](https://github.com/Aarif123456/modern-deedy) |
| **Status** | Actively maintained |
| **Example PDF** | [`My Resume.pdf`](My%20Resume.pdf) |

## ✨ Key Changes

* **Profile photo** in a rounded frame at the top-left header.  
* **Dotted-rule section separators** for improved visual scanning.  
* **Redesigned contact block** (now a tidy two-column table).  
* **ResearchGate icon/link** for academics.  
* Small typographic and spacing tweaks.

> **Preview:** open the bundled `My Resume.pdf` or drop the project into Overleaf and hit <kbd>Recompile</kbd>.

---

## 🚀 Quick Start

```bash
git https://github.com/gunakarchalla/Enhanced-Modern-Deedy-Single-Column-Resume.git
cd ./Enhanced-Modern-Deedy-Single-Column-Resume

# edit resume.tex with your details, then…
xelatex resume.tex          # run twice locally
```

Or simply upload the folder to **Overleaf** (XeLaTeX is pre-selected).

---

## 📁 Project Layout

```
.
├── resume.tex            # main source
├── resume-openfont.cls   # class file (forked & tweaked)
├── profile.jpg           # your head-shot
├── LICENSE               # license file
├── raleway-font.sty      # raleway font sty file
├── lato-font.sty         # lato font sty file
├── font-color.sty        # font color sty file
├── fonts/                # optional local fonts
├── Original Template     # font color sty file
└── My Resume.pdf         # example output
```

---

## 🙏 Acknowledgements

* **modern-deedy** by [Aarif123456](https://github.com/Aarif123456) – the original template.  
* Modifications by **<Gunakar Challa>** (2025).

Happy TeX-ing! 🎉
