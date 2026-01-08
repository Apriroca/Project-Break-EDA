# 🏠 Análisis Exploratorio de Datos (EDA): Mercado Inmobiliario en Valencia
El analisis se basa en datos reales de mercado procedentes de portales inmobiliarios de referencia (Habitaclia, Fotocasa, Milanuncios), correspondientes a annuncios de venta y alquiler en el municipio de Valencia publicados durante 2025.
El objetivo es identificar patrones de precios, zonas tensionadas y la relación entre las características de los inmuebles y su valor de mercado.

## 👥 Equipo de Proyecto
* **Integrante 1** (Gabriel) - Ingesta y Limpieza de Datos - Análisis Estadístico - Visualización y Análisis Geográfico - Documentación y Conclusiones - Presentacion PDF
* **Integrante 2** (Ana) - Ingesta y Limpieza de Datos - Análisis Estadístico - Visualización y Análisis Geográfico - Documentación y Conclusiones - Memoria
* **Integrante 3** (Anaïs) - Ingesta y Limpieza de Datos -  Análisis Estadístico - Visualización y Análisis Geográfico - Documentación y Conclusiones - Main & Readme

---

## 🎯 Hipótesis Principal
Existen diferencias significativas en los precios de venta y alquiler en Valencia en función de la zona geográfica y las características del inmueble (superficie, habitaciones, etc.). 

## 🔍 Preguntas de Investigación
Para validar nuestra hipótesis, el equipo busca responder:
H1: Diferencias de precio por ubicación: Existen variaciones significativas en el precio por metro cuadrado dependiendo del distrito de Valencia.
H2: Independencia del precio unitario respecto al tamaño: El precio por metro cuadrado está determinado por la ubicación de la vivienda y no por su tamaño.
H3: Diferencia de demanda entre alquiler y venta: El mercado de alquiler tiene una demanda relativa mayor que el mercado de venta.
H4: Comportamiento diferenciado por tipo de anunciante: Las preferencias sobre el tipo de operación (venta o alquiler) varían entre anunciantes particulares y profesionales.
---

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías principales:** * `pandas`, `numpy` (Tratamiento de datos)
    * `matplotlib`, `seaborn`, `plotly` (Visualización)
    * `folium` / `geopandas` (Análisis espacial)
    * `scipy.stats` (Estadística)

---

## 📂 Estructura del Repositorio
├── main.ipynb              # Notebook principal con el análisis final
├── Memoria.pdf             # Documento técnico detallado
├── Presentacion.pdf        # Diapositivas de la exposición
├── README.md               # Descripción general del proyecto
└── src/                    # Recursos y código fuente
    ├── data/               # Archivos CSV utilizados en el análisis
    ├── img/                # Recursos visuales y gráficas
    ├── notebooks/          # Notebooks de desarrollo y borradores
    └── utils/              # Funciones auxiliares y scripts de limpieza

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
   pip install pandas numpy matplotlib seaborn scipy
   jupyter notebook main.ipynb
