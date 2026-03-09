# Tesis Doctoral TEAC 2026

Repositorio del proyecto de tesis doctoral:

**Sistema tecnológico inteligente para el diagnóstico educativo inclusivo basado en datos**

Autor:  
José Alfredo Martínez Valdés  

Año:  
2026

---

# Descripción del proyecto

Este repositorio contiene el código fuente en **LaTeX** de la tesis doctoral centrada en el desarrollo de un sistema tecnológico inteligente para el diagnóstico educativo inclusivo basado en datos, articulando:

- Inclusión educativa
- Diseño Universal para el Aprendizaje (DUA)
- Accesibilidad digital
- Analítica del aprendizaje

El proyecto integra fundamentos pedagógicos, analítica de datos educativos y diseño de sistemas para apoyar decisiones pedagógicas basadas en evidencia.

---

# Estructura del proyecto
tesis_teac_2026/
│
├── main.tex
├── preamble.tex
│
├── frontmatter/
│ ├── portada.tex
│ ├── resumen.tex
│ ├── abstract.tex
│ ├── agradecimientos.tex
│ └── abreviaturas.tex
│
├── chapters/
│ ├── ch01.tex
│ ├── ch02.tex
│ ├── ch03.tex
│ ├── ch04.tex
│ ├── ch05.tex
│ ├── ch06.tex
│ └── ch07.tex
│
├── references/
│ ├── global.bib
│ ├── ch01.bib
│ ├── ch02.bib
│ ├── ch03.bib
│ ├── ch04.bib
│ ├── ch05.bib
│ ├── ch06.bib
│ └── ch07.bib
│
├── appendices/
│
└── annexes/


---

# Compilación del documento

La tesis se compila utilizando **LaTeX + Biber**.

Secuencia recomendada:
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex


O usando `latexmk`:
# Dependencias principales

El proyecto utiliza, entre otros, los siguientes paquetes:

- babel
- biblatex (estilo APA)
- tikz
- geometry
- hyperref
- cleveref
- booktabs
- longtable
- adjustbox

---

# Licencia

Este repositorio contiene material académico en desarrollo correspondiente a una tesis doctoral.

Uso permitido exclusivamente con fines académicos y de investigación.

---

# Contacto

Autor:  
José Alfredo Martínez Valdés
