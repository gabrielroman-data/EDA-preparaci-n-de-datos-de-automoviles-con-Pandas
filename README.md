# Análisis exploratorio inicial (EDA): Preparación de datos de automóviles con Pandas

Este repositorio contiene un **Jupyter Notebook (Google Colab)** que documenta un flujo de trabajo de **Análisis exploratorio inicial (EDA)**, enfocado en la limpieza y estructuración de un dataset de automóviles.

El objetivo es transformar datos crudos en un DataFrame utilizable, listo para modelado predictivo de regresión.

---

## 📊 Contexto del Dataset y Desafíos

El conjunto de datos utilizado es el de **Automóviles Imports-85** (obtenido del repositorio de UCI Machine Learning).

El archivo CSV original presentó desafíos comunes del mundo real:

1.  **Valores faltantes atípicos:** los valores nulos estaban codificados con el carácter **'?'**.
2.  **Ausencia de encabezados:** el archivo carecía de la fila de nombres de columna.

## ⚙️ Flujo de trabajo implementado (Pasos clave)

El notebook documenta los siguientes pasos cruciales para la preparación de datos:

1.  **Carga de Datos:** importación directa del CSV desde una URL, especificando `header=None`.
2.  **Estructuración:** asignación de **26 nombres de columna** significativos (por ejemplo, `price`, `engine-size`, `wheel-base`).
3.  **Limpieza de Faltantes:** sustitución de todos los caracteres **'?'** por el estándar **`np.nan`** (Not a Number) de NumPy.
4.  **Exploración:** uso de `df.info()` y `df.describe()` para evaluar la calidad, los tipos de datos y las estadísticas descriptivas de las variables.

---

## 🛠️ Herramientas Utilizadas

* **Python:** lenguaje principal.
* **Pandas:** para manipulación y análisis de datos.
* **NumPy:** para manejo de valores numéricos y `NaN`.

---

## 🚀 Cómo Usar / Visualizar el Notebook

Puedes ver el código y los resultados de dos maneras:

1.  **Visualización directa en GitHub:** el archivo `.ipynb` es renderizado automáticamente por GitHub.
2.  **Abrir en Google Colab:** haz clic en el siguiente *badge* para abrir y ejecutar el *notebook* directamente en Google Colab:
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xerDH_E5tEdfysZ8KbY3agFq9FMZZONF?usp=sharing)
