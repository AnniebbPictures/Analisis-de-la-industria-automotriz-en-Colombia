📊 Análisis de la Industria Automotriz en Colombia
Por: Juanita Merchá y Annie Bonilla (Grupo 2)

Este repositorio contiene el desarrollo del proyecto “Análisis de la industria automotriz en Colombia”, cuyo propósito es integrar, explorar y limpiar diversas bases de datos oficiales para preparar un conjunto de información confiable que permita futuros análisis sobre el comportamiento del sector automotor en el país.
🚗 ¿De qué trata el proyecto?
El proyecto se centra en comprender el contexto comercial y demográfico relacionado con la industria automotriz en Colombia. Para esto se utilizan tres fuentes de datos provenientes de entidades oficiales, relacionadas con:
El comercio al por menor
El sector automotor
La población colombiana por departamento
Antes de analizar estas fuentes, fue necesario pasar por un proceso completo de exploración, limpieza y estandarización, ya que los archivos originales contenían inconsistencias, datos faltantes, errores de formato y diferencias estructurales entre hojas.
🎯 Objetivos del proyecto
Unificar y comprender las diferentes bases de datos relacionadas con el sector automotriz.
Identificar problemas comunes en los datos, como valores nulos, duplicados, errores tipográficos, formatos inconsistentes y outliers.
Aplicar técnicas de limpieza y transformación para dejar las bases listas para análisis posteriores.
Documentar claramente el proceso dentro de un Jupyter Notebook, explicando cada decisión realizada.
Generar versiones limpias de cada tabla, organizadas y en formato CSV para fácil reutilización.
📁 ¿Qué contiene este repositorio?
📌 1. Notebook principal
cleaning_notebook.ipynb
Incluye todo el desarrollo del proyecto:
Carga de los archivos Excel originales
Exploración de datos (EDA)
Limpieza y estandarización
Conversión de tipos
Normalización de nombres
Manejo de datos faltantes
Identificación de outliers
Exportación final de los archivos limpios
Toda la lógica está explicada en celdas de markdown.
📌 2. Datos utilizados (raw data)
El proyecto trabaja con las siguientes bases de datos:
Encuesta Mensual de Comercio – EMC (Tabla 1)
Índices de ventas reales por departamento y actividad económica.
Encuesta Mensual de Comercio – Vehículos automotores (Tabla 2)
Información correspondiente al subsector automotriz.
Censo Nacional de Población y Vivienda – CNPV 2018 (Tabla 3)
Datos demográficos por departamento, incluyendo distribución por sexo y grupos de edad.
Estas bases se incluyeron en formato Excel.
📌 3. Datos limpios (clean data)
El repositorio contiene archivos CSV generados después de aplicar todos los procesos de limpieza.
Estos archivos están listos para ser usados en:
Análisis descriptivo
Visualizaciones
Modelos predictivos
Cruces entre fuentes
Dashboards o reportes
🧰 Tecnologías utilizadas
Python
Pandas
NumPy
Jupyter Notebook
Excel
Git / GitHub
📝 Conclusión
Este repositorio constituye una base sólida para el estudio de la industria automotriz en Colombia. Gracias a la limpieza y organización de los datos, ahora es posible realizar análisis confiables que conecten información económica y demográfica para obtener una visión más completa del comportamiento del sector.
