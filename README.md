# tesis_teac_2026

Tesis doctoral en LaTeX sobre diagnóstico educativo inclusivo basado en datos.

## Estructura
- `main.tex`: documento principal
- `preamble.tex`: configuración general
- `chapters/`: capítulos
- `references/`: bases bibliográficas `.bib`
- `frontmatter/`: portada, resumen, abstract, etc.

## Compilación
```bash
latexmk -pdf -interaction=nonstopmode main.tex
biber main
latexmk -pdf -interaction=nonstopmode main.tex