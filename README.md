## 📌 Tabla de Contenidos
- [Contexto del Proyecto](#-contexto-del-proyecto)
- [Arquitectura y KPIs Principales](#-arquitectura-y-kpis-principales)
- [Hallazgos Ejecutivos Clave](#-hallazgos-ejecutivos-clave)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Autor](#-autor)

---

## 🎯 Contexto del Proyecto
Este proyecto simula un análisis de negocio integral para la plataforma de entregas *Rappi*, orientada a optimizar la toma de decisiones estratégicas. El objetivo principal fue auditar los canales de adquisición de usuarios, el retorno de inversión (ROI) en marketing y la rentabilidad por categoría de producto a lo largo del periodo analizado.

## 📈 Arquitectura y KPIs Principales
El modelo de datos incluye tablas dimensionales y de hechos (catalog_clean, Dim_Calendar, orders_clean, etc.) para calcular métricas financieras clave:
* *Revenue Total (Ingresos):* $347.83 mil
* *Profit Total (Ganancia neta):* $215.60 mil
* *Gasto en Marketing:* $610.13 mil
* *Ticket Promedio:* $403.52

## 🔍 Hallazgos Ejecutivos Clave
* *Margen de Ganancia Neto:* Se situó de forma global en un *11.47%*, permitiendo evaluar la eficiencia operativa.
* *Inversión en Marketing:* Se identificó una distribución equilibrada entre los canales Social, Organic y Paid Search.
* *Pruebas A/B (Checkout):* El análisis de impacto en el flujo de pago (A/B Test Checkout) arrojó que no existió una variación estadísticamente significativa ($p = 0.4319$), lo que ayudó a descartar falsas suposiciones en la conversión.
* *Rendimiento por Categoría:* La categoría Electrónica y Hogar lideran el volumen de ventas y generación de valor absoluto frente a otras líneas de productos.

## 🗂️ Estructura del Proyecto
```text
analisis_datos_rappi/
│
├── proyecto_final_rappi.pbix   # Archivo principal del tablero de Power BI
└── README.md                   # Documentación y presentación del proyecto
