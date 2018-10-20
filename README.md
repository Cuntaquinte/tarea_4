# Visual-A
datasets VA
## README

Tarea 4 (Oct 19, 2018)

Autor: 
## Carlos Moreno Ibarguen  

La visualización se encuentra disponible en Github en el siguiente enlace:

- https://cuntaquinte.github.io/tarea_4/index.html

Requisitos
-https://d3js.org/d3.v5.min.js


# Contexto
Fuente: Secretaría de Seguridad y Convivencia Municipio de Palmira con Datos de Policía, Sijin, CTI, Fiscalía, Medicina Legal
*Información Sujeta a Cambios.

Fuente: Tabla elaborada Secretaría de Seguridad, Convivencia y Cultura Ciudadana con datos del Observatorio de Seguridad, Convivencia y Cultura Ciudadana de Informe Consolidado Municipio de Palmira 2008-2016.
*2017 Secretaría de Seguridad y Convivencia Municipio de Palmira con Datos de Policía, Sijin, CTI, Fiscalía, Medicina Legal

Los datos originales estan disponibles en:

- https://www.datos.gov.co/Seguridad-y-Defensa/Estadistica-de-Homicidios-En-la-Ciudad-de-Palmira-/cfbu-if5n

PreProcesados:  
- https://github.com/Cuntaquinte/tarea_4/tree/master/data

# Objetivos del proyecto (Tarea Principal) y tecnologías usadas:
El objetivo del proyecto es generar una visualización  que permita ver los detalles de datos temporales, en este caso se descargaron datos referentes a cifras de asesinatos en la ciudad de Palmira.

- La técnologia utilizada fue html, css,javascript + libreria D3 V3. Los datos se manipularon en los formatos csv.


# Tareas Secundarias:
- Determinar en que momento del año hubo mas o menos asesinatos en la ciudad de Palmira.


# Analisis de los datos
## Preprocesamiento de datos. 
Se organizaron los datos por resumen anuales en el siguiente formato
- year 	total_kills (asesinatos por año)
- year 	month	kills (asesinatos por mes)

## What?
Los datos se obtuvieron de un Dataset tipo Tabla.
### Tipos de atributos
- year:			Ordenado - Ordinal - Secuencial  (Representa los años durante los datos fueron registrados)
- month:		Ordenado - Ordinal - Secuencial   ciclico (Representa los meses durante los datos fueron registrados), a pesar de ser ordinal, secuencial puede ser tratado como dato categorico.
- total_kills:	Ordinal - Secuencial (Representa las cifras de asesinatos resumidos de manera anual.)
- kills:		Ordinal - Secuencial (Representa las cifras de asesinatos por mes.)

## Why?
- Analyze - Consume- Present >> features
- Search - Discover  >> Trends

## How?
### Marcas 
- Line

### Canales
-   Color-Hue
-   Pos X
-   Pos Y


## Licencia MIT
[MIT Licence] https://github.com/Cuntaquinte/midterm-bonus/blob/master/LICENSE

