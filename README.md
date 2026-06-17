# Dashboard de Análisis Estratégico Comercial 📊
**Por: Ing. Angela Vargas**

Este proyecto presenta una solución integral de Data Analytics e Ingeniería de Datos para el análisis de la distribución de microcréditos en el departamento de Santander, Colombia. El pipeline transforma datos públicos crudos en un tablero de control ejecutivo enfocado en Data Storytelling para la toma de decisiones institucionales.
## 🖼️ Vista Previa del Dashboard
<img width="1431" height="803" alt="image" src="https://github.com/user-attachments/assets/aa3ef49d-88a1-4e7a-b7ba-8863046ad1c7" />

## Objetivo del Proyecto
Automatizar el procesamiento y limpieza de datos provenientes del portal oficial de Datos Abiertos Colombia y diseñar un informe gerencial interactivo. El objetivo es identificar la concentración geográfica de los créditos, los sectores económicos más beneficiados y evaluar el impacto social mediante la brecha de género de los beneficiarios.

## Stack Tecnológico
* **Python(Pandas):** Extracción, normalización y transformación de datos (Pipeline ETL).
* **Power BI Desktop:** Modelado de datos, diseño de interfaz ejecutiva y visualización.
* **Power Query (M):** Ajustes menores de tipos de datos y optimización de carga.


## KPIs e Indicadores Clave
El informe permite monitorear:
1.  **VVolumen de Créditos:** Monitoreo del total de microcréditos otorgados en la región (2,096 registros).
2.  **Impacto de Género:** isualización directa de la distribución del beneficio entre Mujeres, Hombres y Personas Jurídicas, destacando el liderazgo del segmento femenino.
3.  **Participación por Macrosector:** Identificación de las industrias que más demandan recursos (liderado fuertemente por Comercio e Industrias Manufactureras).
4.  **TConcentración Territorial:** Top 10 de municipios con mayor asignación de recursos en Santander.

## Estructura del Modelo
ETL con Python: Se desarrolló un script para limpiar caracteres especiales, convertir nombres de columnas a formato estándar (snake_case), homologar las categorías de género y exportar un dataset 100% consistente.

Visualización en Power BI: Se aplicaron principios de diseño de UI/UX para dashboards (paleta de colores corporativa, uso de tipografías legibles y distribución en tarjetas con relieve) para asegurar una experiencia de usuario ejecutiva.

## Acceso al Proyecto
##  Visualización Interactiva
Puedes interactuar con el informe en tiempo real a través del siguiente enlace:

👉 **[Ver Dashboard Interactivo (Power BI Web)](https://app.powerbi.com/view?r=eyJrIjoiNDQ2NDNjMjItMWE5MS00ZGM3LTk0M2EtYzMwNGQ0OTgyNTRhIiwidCI6IjgwMDc3YmJjLWJjNWEtNDc3NS04NzA4LTIwODkyNjVjMDAzMyIsImMiOjR9)**

## 📂 Repositorio de Archivos
* **Archivo del tablero:** [Descargar Informe Comercial.pbix](./InformeMypes.pbix)
* **Archivo fuente:** [LINEA_DE_CREDITO_PARA_MYPES_SANTANDER_20260612.csv](./LINEA_DE_CREDITO_PARA_MYPES_SANTANDER_20260612.csv)
* **Notebook de análisis y limpieza:** [limpieza_datos.ipynb](./ProyectoFinanciero.ipynb)

*Nota: Este proyecto forma parte de mi portafolio profesional como Ingeniera de Sistemas.*