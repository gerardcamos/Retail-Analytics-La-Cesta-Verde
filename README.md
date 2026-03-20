# 🛒 Optimización de Retail: Proyecto "La Cesta Verde"

![Analítica de Datos](https://img.shields.io/badge/Focus-Data_Analysis-green) 
![SQL](https://img.shields.io/badge/SQL-SQLite-blue) 
![Python](https://img.shields.io/badge/Python-GoogleColab-yellow) 
![Power BI](https://img.shields.io/badge/BI-Power_BI-orange)

## 📋 Resumen Ejecutivo
Este proyecto analiza una facturación de **39,8M €** y más de **2 millones de transacciones** para la distribuidora "La Cesta Verde". El objetivo principal fue diagnosticar una caída crítica del 82% en los ingresos anuales y diseñar una estrategia de recuperación basada en modelos de asociación de productos.

---

## 🎯 Desafíos del Negocio
* **Caída de ingresos:** Descenso de 6,7M € (Enero) a 1,1M € (Diciembre).
* **Riesgo de Concentración:** El 93% de las ventas dependían de un solo departamento.
* **Bajo Ticket Medio:** Valor promedio por pedido de 19,34 €, indicando compras de conveniencia.

---

## 🛠️ Stack Tecnológico
* **SQL (SQLite):** Auditoría financiera, limpieza de datos y análisis de Pareto.
* **Python (Pandas):** Implementación de *Market Basket Analysis* (Reglas de Asociación).
* **Power BI:** Creación de Dashboards interactivos y grafos de red para visualización de sinergias.
* **Excel:** Gestión de metadatos y dimensiones de catálogo.

---

## 📁 Estructura del Repositorio
* [📄 **Informe_Ejecutivo.pdf**](./Informe_Final_Gerard_Camos.pdf): Documento de 10 páginas con el análisis de negocio completo. (RECOMENDADO)
* [📂 **01_SQL/**](./01_SQL/): Scripts de auditoría y extracción de KPIs.
* [📂 **02_Python/**](./02_Python/): Notebook con el cálculo de métricas de Soporte, Confianza y Lift.
* [📂 **03_Datasets_Procesados/**](./03_Datasets_Procesados/): Salidas en CSV de los análisis realizados.

---

## 💡 Hallazgos y Resultados Clave
1. **Reglas de Asociación:** Se detectaron **399 reglas validadas**. Ejemplo: El *Hummus* y las *Zanahorias Baby* tienen un **Lift de 2,50**, lo que sugiere un potencial de cross-selling inmediato.
2. **Diversificación:** Se identificó la necesidad de traccionar 3.800 referencias de baja rotación usando productos "ancla" (Bananas y Fresas).
3. **Eficiencia Logística:** Propuesta de reubicación de productos en almacén (*Slotting*) basada en afinidad de compra para reducir tiempos de preparación.

---

## 👤 Autor
**Gerard Camós Moratalla**
*Business & Data Analyst*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/gerardcam%C3%B3s/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat-square&logo=gmail)](gerardcm8@gmail.com)

---
*Nota: Debido al tamaño de la base de datos original (414 MB), el archivo .db no se encuentra en este repositorio, pero los resultados están pre-renderizados en el Notebook de Python y en el Informe PDF.*
