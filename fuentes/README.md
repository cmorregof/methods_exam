# Fuentes de los PDF

Cada `.tex` se compila con XeLaTeX desde esta carpeta (usa Latin Modern, que viene con cualquier TeX Live o MacTeX):

```
xelatex raices-A-kepler.tex && xelatex raices-A-kepler.tex
```

Se compila dos veces para que el pie diga «página x de y». Si cambias un `.tex`, copia el PDF nuevo a la carpeta del parcial como `parcial.pdf`.
