# Proyecto_grupal_Bio_DataScience_Latam_Fernando
Proyecto grupal del Bootcamp de Data science de Henry en el que se busca predecir las emisiones de CO2 en los próximos 30 años contados a partir del 2022

# Objetivos

Brindar asesoramiento a las entidades públicas y privadas acerca del consumo energético, emisiones de CO2.
Potencializar a los países hacia el uso de energías renovables.
Aportar a la reducición de la tendencia actual de emisiones de gases de efecto invernadero y otros contaminantes que contribuyen al cambio climático.
Posibilidad de tener energía eléctrica en ciudades remotas.

# Tecnologias

STACKs

- Python
Utilizamos la librería pandas de este lenguaje de programación para la lectura, el análisis y el procesamiento de los datos recopilados de distintas fuentes.

- MySQL
Se utilizará la aplicación para realizar el proceso de ETL definitivo y visualizar consultas rápidamente.

- Glue
Se normaliza los datos usando la consola de Python

- Redshift
Esta plataforma nos permitirá realizar consultas interactivas para facilitar el análisis de los datos. Redshift no tiene servidor, de manera que no es  necesario administrar infraestructura.

- S3
Se crearán dos buckets S3, uno almacenará los datos en crudo y el otro los datos normalizados

- Power BI
Herramienta para la visualización y consulta de la información procesada.

# ALCANCE

Ingesta de diferentes datasets con información a partir del año 1930 para realizar predicciones del uso de energías renovables y de las emisiones de CO2.
La consulta brinda información del tipo de energía que es consumida y generada, también su respectiva generación de CO2 anual a nivel nacional, regional y mundial.

# RESTRICCIONES

El análisis proporcionado no será anterior al año 1930.
La consulta no brindará información a nivel local de cada nación.
La carga de datos será por lotes en diferentes formatos.

# Metología del Trabajo

- ENFOQUE METODOLÓGICO

El trabajo se sustenta bajo un enfoque cuantitativo con el que se busca establecer relaciones entre las variables población, consumo energético, emisiones de C02 y potencial de los países para la priorización del uso de energías renovables.

- ESTRATEGIA DE INVESTIGACIÓN

Se usó el estudio de caso como estrategia de investigación. Se analizó la información existente sobre la población, consumo energético, emisiones de C02 y potencial de los países para la priorización del uso de energías renovables de diversas bases de datos.

El alcance de este estudio es correlacional ya que se tiene como hipótesis las existencias de correlación entre cada una de las siguientes variables a saber, la población, consumo energético, emisiones de C02 y potencial de los países para la priorización del uso de energías renovables. Se estimará o predecirá las necesidades de consumo energético y las emisiones de CO2 a nivel mundial y en cada país.

Como herramientas estadísticas se utilizará el lenguaje Python para los procesos de Extracción, transformación y limpieza (ETL) y el Machine learning para la estimación o predicción de las necesidades de consumo energético y las emisiones de CO2 a nivel mundial y en cada país. Se hará uso de un Sitio Web publicado desarrollado en php con base de datos MySQL

- TÉCNICAS DE RECOLECCIÓN DE INFORMACIÓN.

Para estimar o predecir las necesidades de consumo energético y las emisiones de CO2 a nivel mundial y en cada país, se recopilará dataset y bases de datos de diversas fuentes especializadas en el registro de información de consumo de energía eléctrica, la producción de energía según fuentes y de emisiones de CO2 de cada país.
