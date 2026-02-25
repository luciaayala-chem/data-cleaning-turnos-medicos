# data-cleaning-turnos-medicos
Limpieza de datos y control de calidad sobre dataset simulado de turnos médicos 

## Objetivo
Realizar la limpieza y estandarización de un dataset simulado de turnos médicos que contiene errores clásicos y luego analizar la información con herramientas de Excel.

## Descripción del dataset
La base de datos incluye las siguientes características del turno:
- Paciente
- Datos de contacto
- Ciudad
- Fecha y hora del turno
- Servicio médico
- Estado del turno
- Precio

El dataset fue diseñado con errores típicos de bases administrativas reales.

## Problemas incluídos
- Fechas en distintos formatos
- Duplicados exactos y parciales
- Inconsistencias en nombres de pacientes
- Emails mal formados
- Servicios escritos con abreviaciones o errores ortográficos
- Turnos confirmados sin fecha
- Turnos cancelados con precio cobrado
- Valores de precio en cero para servicios pagos
- Inconsistencias en estados de turno

## Proceso de limpieza
- Normalización de mayúsculas y acentos
- Estandarización de formatos de fecha y texto
- Corrección de errores en datos de contacto
- Corrección de categorías (servicios y estados)
- Eliminación de duplicados
- Validación de consistencia lógica entre columnas


## Análisis
Una vez obtenida la base limpia:
- Análisis de cantidad de turnos por servicio
- Análisis de ingresos por servicio
- Análisis por ciudad

Se utilizaron tablas dinámicas y funciones de Excel para obtener los resultados.


## Herramientas utilizadas
- Microsoft Excel
- Power Query
