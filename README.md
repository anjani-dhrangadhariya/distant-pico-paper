# JAMIA LaTeX paper template

## Compile

The file `main_paper.tex` can be compiled using pdflatex or latex. However, these two compiler do not compile an output as the one required because they don't use Time News Roman font. LuaLaTeX or XeLaTeX compilers can be used instead. ([Texmaker] provides all the previous options.)

To compile the project using LuaLaTeX:
```bash
$ lualatex amia-paper.tex
$ bibtex amia-paper
$ lualatex amia-paper.tex
$ lualatex amia-paper.tex
```