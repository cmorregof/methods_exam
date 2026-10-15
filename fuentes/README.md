# Fuentes de los PDF

Cada `.tex` se compila con XeLaTeX desde esta carpeta (Latin Modern, que viene con TeX Live o MacTeX):

```
xelatex taylor-gps.tex && xelatex taylor-gps.tex
```

Se compila dos veces para que el pie diga «página x de y». Si cambias un `.tex`, copia el PDF nuevo a la carpeta del parcial como `parcial.pdf`.
