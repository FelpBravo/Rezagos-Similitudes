# Proceso de Similitud de Rezagos

Este repositorio contiene un proceso de similitud de datos de rezagos y afiliados utilizando PySpark en un entorno de Oracle Cloud Infrastructure (OCI).

## Descripción

El proceso tiene como objetivo calcular la similitud entre registros de rezagos y afiliados, basándose en varios criterios, como nombres, apellidos y otros campos relevantes. El resultado se almacena en archivos Parquet y se guardan en un bucket de OCI.

## Requisitos

Asegúrate de tener instalado lo siguiente antes de ejecutar el código:

- Oracle Cloud Infrastructure (OCI) con acceso a los buckets especificados en el código.
- Python con las bibliotecas necesarias, incluyendo PySpark y fuzzywuzzy.

## Uso

Para ejecutar el proceso, sigue estos pasos:

1. Asegúrate de tener todos los requisitos previos configurados.

2. Ejecuta el código proporcionado en un entorno de PySpark compatible.

3. El proceso cargará los datos de rezagos y afiliados desde el bucket de OCI y calculará la similitud entre ellos.

4. Los resultados se guardarán en diferentes buckets según el dígito verificador y en un bucket final consolidado.

## Configuración

Puedes ajustar la configuración del proceso modificando el objeto `command` en el código. Esto incluye la configuración de las instancias de Spark, los buckets de almacenamiento y otros parámetros relacionados con el proceso.

## 
**Nota Importante**: Los archivos sensibles no han sido subidos al repositorio o han sido ocultados por razones de seguridad.

Estos archivos contienen información confidencial, como contraseñas o claves de acceso, y no deben estar disponibles públicamente en un repositorio de código abierto.

