# Trabajo final · Girar un espín con un campo eléctrico

Tres discretizaciones de la resonancia de espín por dipolo eléctrico (EDSR), cotas que el computador verifica para la separación Zeeman y el elemento de Rabi, y un mapa certificado de dónde fallan las fórmulas de primer orden. Samuel Camilo Merchán · dirige Carlos Orrego.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cmorregof/methods_exam/blob/main/trabajo-final-espin/trabajo_final_espin.ipynb)

- **Guía:** [`guia.pdf`](guia.pdf) (fuente en `fuentes/trabajo-final-espin.tex`). Cuatro piezas, una por semana, y una opcional sobre sistemas con espín–órbita fuerte.
- **Cuaderno:** [`trabajo_final_espin.ipynb`](trabajo_final_espin.ipynb). Corre completo en unos 20 segundos.
- **Plantilla del artículo:** [`preprint/espin_preprint.tex`](preprint/espin_preprint.tex), con sus dos figuras (`fig_mapa.pdf`, `fig_convergencia.pdf`). Súbelas juntas a Overleaf y compila con pdflatex. Si cambias el cuaderno, las celdas B3 y C5 vuelven a generar las figuras.
- **Datos:**
  - Constantes físicas: CODATA 2022, a través de `scipy.constants`. El cuaderno las compara con NIST en línea.
  - Parámetros de los dispositivos: copiados de Nowack et al. (2007), Nadj-Perge et al. (2010), Fasth et al. (2007) y Vurgaftman et al. (2001). Están en [`datos/parametros_dispositivos.csv`](datos/parametros_dispositivos.csv), con la fuente de cada número, y congelados en la celda 0 del cuaderno.
  - Constantes de H³⁵Cl: NIST Chemistry WebBook, como en el parcial `hermite-hcl`. Copia congelada.

Entregas: jueves 5, 12 y 19 de noviembre. Entrega final y sustentación: jueves 26 de noviembre de 2026.
