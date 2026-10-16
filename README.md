# Matías Gabriel Picón — Personal Portfolio & LaTeX CV (`x7reme13.github.io`)

Personal bilingual (Spanish / English) portfolio website for **GitHub Pages** (`https://x7reme13.github.io`) and **2-column LaTeX Curriculum Vitae** sources + compiled PDFs.

## Repository Structure

```text
.
├── index.html                    # Main bilingual portfolio page (ES / EN toggle + Dark/Light mode)
├── assets/
│   ├── style.css                 # Responsive zero-dependency CSS stylesheet
│   └── app.js                    # i18n dictionary (ES/EN), theme switcher, and project category filter
└── cv/
    ├── cv_es.tex                 # 2-column LaTeX source (Spanish)
    ├── cv_en.tex                 # 2-column LaTeX source (English)
    ├── Matias_Picon_CV_ES.pdf    # Compiled Spanish CV PDF
    └── Matias_Picon_CV_EN.pdf    # Compiled English Resume PDF
```

## Recompiling the LaTeX CVs

Using [Tectonic](https://tectonic-typesetting.github.io/):

```bash
cd cv
tectonic cv_es.tex && cp cv_es.pdf Matias_Picon_CV_ES.pdf
tectonic cv_en.tex && cp cv_en.pdf Matias_Picon_CV_EN.pdf
```
