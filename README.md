# Estudio de Mortalidad

## Objetivo  
Analizar indicadores globales de mortalidad, fertilidad y crecimiento poblacional para identificar tendencias demográficas clave que puedan apoyar la toma de decisiones en políticas públicas, salud y desarrollo social.

---

## Tabla de Contenidos
- [Introducción](#introducción)  
- [Fuentes de Datos](#fuentes-de-datos)  
- [Procesamiento y Limpieza](#procesamiento-y-limpieza)  
- [Análisis y Visualización](#análisis-y-visualización)  
- [Hallazgos Clave](#hallazgos-clave)  
- [Requisitos](#requisitos)  
- [Uso](#uso)  
- [Contribuciones](#contribuciones)  
- [Autor](#autor)  

---

## Introducción  
Este proyecto tiene como finalidad realizar un análisis exploratorio de datos de mortalidad y fertilidad a nivel mundial. A través de técnicas de análisis y visualización, se busca encontrar patrones relevantes que permitan entender el comportamiento demográfico de diferentes regiones y países.

---

## Fuentes de Datos  
- **Archivo Utilizado:**  
  `SYB66_246_202310_Population Growth, Fertility and Mortality Indicators.csv`  
- **Fuente:**  
  [United Nations - World Population Prospects](https://www.un.org/development/desa/pd/)  
- Este archivo incluye indicadores de crecimiento poblacional, fertilidad, mortalidad infantil, esperanza de vida, entre otros.

---

## Procesamiento y Limpieza  
El conjunto de datos fue procesado utilizando Python y herramientas de análisis de datos en un entorno Jupyter Notebook.  
Pasos realizados:
- Eliminación de valores nulos.
- Conversión de tipos de datos.
- Filtrado por regiones o años relevantes.
- Homogeneización de nombres y estructuras para facilitar el análisis.

---

## Análisis y Visualización  
Se utilizaron herramientas como Matplotlib y Seaborn para generar gráficos que representen visualmente:
- Comparativas de esperanza de vida por región y género.
- Evolución de tasas de mortalidad infantil.
- Cambios en tasas de fertilidad a lo largo del tiempo.

---

## Hallazgos Clave (Ejemplos)
- Se observa una **tendencia decreciente** en la tasa de mortalidad infantil en la mayoría de las regiones del mundo.
- La **esperanza de vida ha aumentado** globalmente, con mayores incrementos en países en desarrollo.
- A nivel mundial, la **tasa de fertilidad ha disminuido**, lo que puede tener implicaciones importantes en el crecimiento poblacional futuro.

---

## Requisitos  
Para ejecutar el notebook, necesitas tener instalado:

- Python 3.x  
- Jupyter Notebook o Jupyter Lab  
- Pandas  
- Matplotlib  
- Seaborn  

Instalación rápida:
```bash
pip install pandas matplotlib seaborn jupyter
```

---

## Uso  
1. Clona este repositorio:
```bash
git clone https://github.com/tu_usuario/estudio-mortalidad.git
```
2. Abre el notebook:
```bash
jupyter notebook "Estudio de Mortalidad.ipynb"
```
3. Ejecuta las celdas en orden para procesar los datos y visualizar los resultados.

---

## Contribuciones  
¿Tienes ideas para mejorar este análisis?  
¡Eres bienvenido! Puedes abrir un issue o enviar un pull request con mejoras en código, visualizaciones o interpretación de datos.

---

## Autor  
**José Eduardo Saucedo Martínez**  
