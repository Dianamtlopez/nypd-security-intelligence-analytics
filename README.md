# Desarrollo de una herramienta de análisis y visualización de eventos críticos para la optimización de protocolos de seguridad privada

## 📝 Descripción del Proyecto
Este repositorio contiene el desarrollo técnico del Trabajo Fin de Máster de **Diana María Toro López** para el Máster en Análisis y Visualización de Datos Masivos de la **UNIR**. 

El proyecto consiste en una herramienta de software original que transforma la gestión de incidentes en el sector de la seguridad física —tradicionalmente reactiva— en un modelo **proactivo basado en datos**. Utilizando registros de **NYC Open Data**, el sistema identifica "puntos calientes" y patrones de vulnerabilidad mediante lógica avanzada de procesamiento y visualización.

---

## 🛠️ Arquitectura de la Solución
El sistema sigue una arquitectura de tres capas para garantizar eficiencia y escalabilidad:

1. **Capa de Datos:** Consumo automatizado vía API del dataset "NYPD Complaint Data Historic" (100,000 registros).
2. **Capa de Lógica (Back-end):** Procesamiento en **Python 3.10** (Pandas/NumPy) para limpieza, normalización y ejecución de algoritmos de detección de anomalías.
3. **Capa de Presentación (Front-end):** Dashboard interactivo en **Power BI** diseñado bajo principios de *Visual Analytics*.

---

## 🚀 Resultados Obtenidos
Basado en las pruebas de estrés y validación funcional (Tabla 1 de la memoria), el software presenta las siguientes mejoras frente a procesos manuales:

| Métrica de Análisis | Mejora (%) |
| :--- | :--- |
| **Tiempo de detección de anomalías** | **72.3%** |
| **Precisión en identificación de KPIs** | **26.5%** |
| **Generación de mapas de calor** | **95.6%** |
| **Promedio General de Mejora** | **64.8%** |

---

## 📁 Estructura del Repositorio
* `Data_Processing_Vulnerability_Patterns_01.ipynb`: Cuaderno Jupyter con el proceso ETL completo.
* `nypd_security_intelligence.csv`: Dataset procesado listo para consumo.
* `Visualizacion Power Bi.pbix`: Archivo de visualización con lógica DAX implementada.
* `requirements.txt`: Librerías de Python necesarias para replicar el entorno.

---

## ⚖️ Privacidad y Cumplimiento (RGPD)
Este proyecto ha sido diseñado bajo el principio de **Privacy by Design**. 
* **Origen:** Datos de fuentes públicas (Open Data).
* **Protocolo:** Los datos carecen de identificadores personales en su estructura original y han sido sometidos a procesos de anonimización, cumpliendo con el **Considerando 26 del RGPD** y la **LOPDGDD**.

---

## 👤 Información del Autor
* **Autor:** Diana María Toro López
* **Director:** Felix Ladstätter
* **Institución:** Universidad Internacional de La Rioja (UNIR)
* **Fecha:** 15 de abril de 2026
