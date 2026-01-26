# PMO Automation: Dashboard Ejecutivo de Control de Proyectos (EVM)

## 📌 Descripción
Este repositorio contiene un **Artefacto Técnico** desarrollado en Python para la automatización de la analítica en Oficinas de Gestión de Proyectos (PMO). El script integra los estándares de **Gestión del Valor Ganado (EVM)** del PMI con técnicas modernas de procesamiento de datos para eliminar la latencia en el reporte ejecutivo.

El objetivo es transformar datos maestros de Excel en un cuadro de mando dinámico que permita visualizar el desempeño en tiempo real, garantizando una **Única Fuente de Verdad (SSOT)**.

## 🚀 Características Principales
- **Automatización ETL:** Limpieza y extracción automática de datos desde archivos Excel estandarizados.
- **Análisis de Desempeño:** Cálculo y visualización de Curvas S (Plan vs. Real vs. Ganado).
- **Indicadores de Control:** Generación de gráficos de varianza (CV/SV) e índices de eficiencia (CPI/SPI).
- **Escalabilidad:** Diseñado para adaptarse a proyectos de infraestructura, energía y tecnología.

## 🛠️ Tecnologías Utilizadas
- **Lenguaje:** Python 3.x
- **Librerías:** - `pandas`: Manejo y transformación de estructuras de datos.
  - `matplotlib`: Generación de visualizaciones de grado profesional.
  - `numpy`: Cálculos vectorizados de varianza.
  - `openpyxl`: Interfaz de lectura para archivos `.xlsx`.

## 📂 Estructura del Proyecto
- `/scripts/InformeProyecto.py`: Script principal de procesamiento y visualización.
- `/data/Detalle_CurvaS_Subestacion.xlsx`: Plantilla de datos de ejemplo.
- `/output/`: Directorio donde se almacenan los reportes generados.

## 🏁 Instrucciones de Uso
1. **Instalación de dependencias:**
   ```bash
   pip install pandas matplotlib openpyxl numpy
