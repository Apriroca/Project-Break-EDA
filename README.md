# 🏠 Análisis Exploratorio de Datos (EDA): Mercado Inmobiliario en Valencia
El analisis se basa en datos reales de mercado procedentes de portales inmobiliarios de referencia (Idealista, Habitaclia, Fotocasa...), correspondientes a annuncios de venta y alquiler en el municipio de Valencia publicados durante 2025.
El objetivo es identificar patrones de precios, zonas tensionadas y la relación entre las características de los inmuebles y su valor de mercado.

## 👥 Equipo de Proyecto
* **Integrante 1** (Gabriel) - Ingesta y Limpieza de Datos - Análisis Estadístico - Visualización y Análisis Geográfico - Documentación y Conclusiones
* **Integrante 2** (Ana) - Ingesta y Limpieza de Datos - Análisis Estadístico - Visualización y Análisis Geográfico - Documentación y Conclusiones
* **Integrante 3** (Anaïs) - Ingesta y Limpieza de Datos -  Análisis Estadístico - Visualización y Análisis Geográfico - Documentación y Conclusiones

---

## 🎯 Hipótesis Principal
Existen diferencias significativas en los precios de venta y alquiler en Valencia en función de la zona geográfica y las características del inmueble (superficie, habitaciones, etc.). 

## 🔍 Preguntas de Investigación
Para validar nuestra hipótesis, el equipo busca responder:
1.  **Diferencias Geográficas:** ¿Existen brechas relevantes de precio entre los diferentes barrios de Valencia?
2.  **Correlación de Atributos:** ¿Qué relación existe entre el precio y variables como la superficie o el número de habitaciones?
3.  **Extremos de Mercado:** ¿Qué zonas concentran los precios más altos y más bajos en ambas modalidades (venta y alquiler)?
4.  **Tensión de Alquiler:** ¿Se observan patrones de un mercado tensionado donde el alquiler es desproporcionadamente caro respecto a la compra?
---

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías principales:** * `pandas`, `numpy` (Tratamiento de datos)
    * `matplotlib`, `seaborn`, `plotly` (Visualización)
    * `folium` / `geopandas` (Análisis espacial)
    * `scipy.stats` (Estadística)

---

## 📂 Estructura del Repositorio
├── data/               # archivos CSV mensuales de DataVenues
├── notebooks/          # Jupyter Notebooks con el análisis paso a paso
├── src/                # Scripts de Python (limpieza y funciones)
├── results/            # Gráficos y visualizaciones exportadas
└── README.md           # Descripción del proyecto

---


## 📊 Patrones Esperados
* **Variabilidad Territorial:** Alta dispersión de precios entre el centro histórico y las zonas periféricas.
* **Relación Superficie-Precio:** Correlaciones positivas fuertes ($r > 0.7$).
* **Concentración de Valor:** Mayor demanda y precios elevados en zonas céntricas y áreas con servicios consolidados.
* **Efecto Tensión:** Precios de alquiler elevados en relación al precio de venta en barrios con alta rotación o demanda turística/estudiantil.

---

## 🚀 Cómo ejecutar el proyecto
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/Apriroca/Project-Break-EDA.git](https://github.com/Apriroca/Project-Break-EDA.git)
