# Proyecto-contabilium---Reporte-PaidMedia
La empresa Contabilium solicita el proyecto que se realiza la ingesta de datos desde diversas fuentes de información. Posteriormente se deben aplicar las transformaciones necesarias para disponer los datos limpios y visualizarlos en un tablero.

El objetivo principal del proyecto es brindar información para evaluar el rendimiento de las campañas publicitarias de la empresa, lo que permitirá tomar decisiones informadas basadas en datos precisos y actualizados.

## Problemática planteada
La principal situación expuesta por parte de la empresa, radica en la cantidad de horas perdidas al realizar la desconcatenación manual de la información necesaria para el análisis del progreso de los KPIs de la empresa, generando de esta manera una ineficiencia en el proceso.
La segunda problemática presentada es la necesidad de trabajar con información cruzada de las distintas fuentes de datos utilizadas, Google Ads, Meta ads, Registro admin y el Plan de medios y de esta manera realizar el informe con su visualización completa en la herramienta elegida, Looker. Estudio.
Objetivos del proyecto
Automatizar el proceso de desconcatenación y proceso ETL (Extract, Transform, Load) mediante una aplicación construida con Python.
Cruzar varias fuentes de datos para obtener los KIPs de la empresa y producir el informe mensual.
Realice un tablero en looker studio combinando los diferentes archivos, aplicando filtros, dimensiones y métricas en los gráficos solicitados.
Flujo del dato (DFD)
El diagrama del flujo de datos (Data Flow Diagram) es una herramienta visual utilizada en el análisis y diseño de sistemas de información para representar cómo fluye la información a través de un sistema.

El DFD es útil porque proporciona una vista general del sistema y permite identificar problemas en el flujo de datos, redundancias y posibles cuellos de botella.

A continuación vemos gráficamente el DFD desde la extracción hasta la visualización del dato.
![image](https://github.com/facedo20/Proyecto-contabilium---Reporte-PaidMedia/assets/110402210/ed00d7c8-1a48-4240-a9f6-21a9e4faa754)

## Pasos clave del proyecto

1. Realizar la conexión de la data generada por Google Ads a la herramienta de trabajo Looker Studio.
2. Descargar la información de la fuente Meta a una hoja de cálculo Google Sheets.
3. Descargar la información de la fuente admin a una planilla de cálculo en formato excel (.xlsx). Tener presente que se debe mantener el orden y el nombre de encabezado de las columnas.  
4. Abrir la app presionar botón *Open* y seleccionar el archivo generado en el paso anterior.
5. Presionar botón *Run* para ejecutar el trabajo de limpieza, transformación y carga de los datos (ETL).
6. Realizar la carga manual de la data generada en el archivo admin de la hoja de cálculo Google Sheets.
7. Se actualizará el reporte interactivo en Looker Studio para visualizar la información.

## Habilidades técnicas utilizadas

Habilidades técnicas de un ingeniero de datos:

- Conocimientos en bases de datos y programación.
- Capacidad para diseñar y construir sistemas de almacenamiento de datos.
- Experiencia en integración de datos y en la construcción de pipelines de datos.
- Conocimientos en herramientas de visualización de datos.
- Familiaridad con la seguridad de datos y la protección de la privacidad.

Habilidades técnicas de un analista de datos:

- Conocimientos en estadística y análisis de datos.
- Capacidad para trabajar con grandes conjuntos de datos y en herramientas de análisis de datos, como Excel, Python.
- Capacidad para identificar patrones y tendencias en los datos y presentarlos de forma clara y concisa.
- Conocimientos en modelado y visualización de datos.
- Capacidad para trabajar en equipo y comunicar resultados y hallazgos a diferentes audiencias, incluyendo a personas sin conocimientos técnicos.
