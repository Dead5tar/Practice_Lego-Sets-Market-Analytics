# A LEGO Sets Market & Pricing Analytics (Python & Power BI)

## A Resumen del Proyecto
Este proyecto analiza el mercado histórico de los sets de LEGO utilizando **Python, Pandas y Power BI**. El objetivo principal es explorar la economía del juguete, evaluando la relación entre el precio de venta en EE.UU. (`US_retailPrice`), la cantidad de piezas (`pieces`), el costo por unidad de plástico (`price_per_piece`) y la evolución de los temas más populares a lo largo del tiempo.

### A Tecnologías y Herramientas Utilizadas
* **Python & Pandas:** Limpieza de datos nulos, ingeniería de características (cálculo de precio por pieza) y exportación de datos optimizados.
* **Power BI:** Diseño de un dashboard ejecutivo interactivo con KPIs, gráficos de dispersión avanzados y segmentación por categorías (*Slicers*).
* **Business Intelligence (Retail):** Enfoque analítico enfocado en la visualización de valores atípicos (*outliers*) y comportamiento de precios en el mercado de juguetes.

### A Vista Previa del Dashboard (Power BI)
*(Aquí puedes arrastrar o enlazar la captura de pantalla de tu dashboard)*
![Dashboard de LEGO](ruta_de_tu_imagen/dashboard_preview.png)

### A Componentes del Proyecto
1. **`lego_sets.csv`**: Dataset original de Maven Analytics.
2. **`lego_analysis.py`**: Script en Python encargado de procesar, limpiar y generar el archivo optimizado (`lego_sets_clean.csv`).
3. **`lego_dashboard.pbix`**: Archivo fuente del reporte interactivo de Power BI.

### Hallazgos Clave de Negocio
* **Correlación de Escala:** El diagrama de dispersión demuestra cómo los precios escalan de forma no lineal en sets masivos de colección, aislando aquellas franquicias que demandan una inversión superior por parte del consumidor.
* **Dominio de Franquicias:** Las líneas clásicas (*City*, *Star Wars* y *Duplo*) lideran ampliamente el volumen histórico de producción, marcando la pauta de rotación en el mercado retail.

---
*Desarrollado como parte del portafolio de análisis de datos e inteligencia de negocios.*
