# data-science-ml-portfolio
Teaching and project notebooks for ML, DL, and NLP (Google Colab)

## License and usage

The code in this repository is released under the MIT License.  
This means you are free to use, modify, and share the code, including in commercial projects, provided that you include the original copyright notice and license.

All notebooks and materials are primarily intended for educational purposes, such as teaching, learning, and demonstrating data science and machine learning concepts.  

If you use or adapt these materials in your own courses, talks, or projects, a brief attribution to the original author, Mgs. Ivan Acosta, is appreciated.

## Datasets — Rutas públicas (Raw URLs)

Los datasets se encuentran en la carpeta `datasets/`. Para cargarlos directamente desde Google Colab u otro entorno, utiliza las siguientes URLs públicas:

| Taller | Archivo | URL pública |
|--------|---------|-------------|
| Taller 01 | TALLER_01_Dataset_Titanic.csv | `https://raw.githubusercontent.com/ivanacostag02/data-science-ml-portfolio/main/datasets/TALLER_01_Dataset_Titanic.csv` |
| Taller 03 | TALLER_03_Dataset_California_Housing.csv | `https://raw.githubusercontent.com/ivanacostag02/data-science-ml-portfolio/main/datasets/TALLER_03_Dataset_California_Housing.csv` |
| Taller 04 | TALLER_04_Dataset_California_Housing.csv | `https://raw.githubusercontent.com/ivanacostag02/data-science-ml-portfolio/main/datasets/TALLER_04_Dataset_California_Housing.csv` |
| Taller 10 | TALLER_10_Dataset_EncuestasDieta.xlsx | `https://raw.githubusercontent.com/ivanacostag02/data-science-ml-portfolio/main/datasets/TALLER_10_Dataset_EncuestasDieta.xlsx` |

### Ejemplo de uso en Python / Google Colab

```python
import pandas as pd

# Taller 01 — Titanic
url = "https://raw.githubusercontent.com/ivanacostag02/data-science-ml-portfolio/main/datasets/TALLER_01_Dataset_Titanic.csv"
df = pd.read_csv(url)

# Taller 03 / 04 — California Housing
url = "https://raw.githubusercontent.com/ivanacostag02/data-science-ml-portfolio/main/datasets/TALLER_03_Dataset_California_Housing.csv"
df = pd.read_csv(url)

# Taller 10 — Encuestas Dieta (Excel)
url = "https://raw.githubusercontent.com/ivanacostag02/data-science-ml-portfolio/main/datasets/TALLER_10_Dataset_EncuestasDieta.xlsx"
df = pd.read_excel(url)
```
