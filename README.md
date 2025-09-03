# Relativity Paper

Este repositorio contiene un **paper académico sobre la teoría de la relatividad** escrito en LaTeX.  
El documento abarca tanto la **Relatividad Especial** como la **Relatividad General**, incluyendo aplicaciones modernas como GPS, cosmología y agujeros negros.

---

## Contenido

- `relativity.tex` → archivo principal en LaTeX.  
- `relativity.bib` → bibliografía del paper.  
- `images/` → carpeta opcional con figuras usadas en el paper.  
- `.gitignore` → configuración para ignorar archivos temporales de LaTeX.

---

## Compilación

Para compilar el PDF en tu máquina local con `latexmk`:

```bash
latexmk -pdf relativity.tex