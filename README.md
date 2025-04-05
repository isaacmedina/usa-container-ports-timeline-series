# 📦 Análisis de Importaciones en Puertos de EE. UU. (2000–2017)

Este proyecto analiza el comportamiento histórico de las importaciones en toneladas métricas desde el año 2000 al 2017 en los principales puertos de Estados Unidos. Se utilizan técnicas de análisis estadístico, visualización de datos y modelos de predicción para generar información útil para la planificación portuaria y logística.

---

## 📁 Contenido del Proyecto

- `data/container-ports-2000-2017.csv`: Dataset con datos de importación por puerto (extraído de Kaggle).
- `container-ports-2000-2007.ipynb`: Jupyter notebooks para análisis, gráficos, ANOVA y modelos de series temporales.
- `docs/`: Documentación, informes y notas técnicas del análisis.
- `requirements.txt`: Librerias de python requeridas.
- `README.md`: Descripción del proyecto.

---

## 📊 Dataset

El dataset contiene las importaciones en toneladas métricas desde el año 2000 hasta 2017 para más de 60 puertos de Estados Unidos. Las columnas incluyen:

- `U.S. Custom Ports`: Nombre del puerto.
- `Coast`: Región (A = Atlántico, P = Pacífico, G = Golfo).
- `2000` a `2017`: Importaciones anuales por puerto.

---

## 🧪 Análisis Realizado

- **Estadísticas descriptivas** por puerto.
- **Visualización de tendencias** por costa y por puerto.
- **Correlaciones** entre puertos importantes (New York, Los Angeles, Miami, etc.).
- **Modelos ANOVA** para comparar diferencias significativas entre puertos.
- **Modelos de series temporales** (Holt-Winters, regresión exponencial).
- **Pronósticos de importaciones** para años futuros (2018–2022).

---

## 🔧 Requisitos

Este proyecto requiere Python 3 y las siguientes bibliotecas:

```bash
pandas
matplotlib
numpy
scikit-learn
scipy
statsmodels
```

Puedes instalar todas con:

```bash
pip install -r requirements.txt
```

---

## 📈 Aplicaciones

- Planificación estratégica para autoridades portuarias.
- Evaluación del comportamiento comercial entre costas.
- Apoyo a la toma de decisiones en logística y transporte.
- Análisis de tendencias para instituciones como el Canal de Panamá.

---

## 🛠 Autor

Este proyecto fue desarrollado como parte de un análisis aplicado al contexto del Canal de Panamá, dada su relación directa con los puertos de EE. UU. y China.

---

## 📜 Licencia

[MIT](LICENSE)
