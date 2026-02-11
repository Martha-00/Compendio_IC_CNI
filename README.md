# Compendio_IC_CNI
Este repositorio contiene un extracto del compendio de algunos Indicadores Clave (IC) del INEGI, y presenta ejemplos de sintaxis en R Markdown para el cálculo de IC a partir 
de diversas fuentes de información.
El objetivo principal es garantizar la replicabilidad de los cálculos y establecer un repositorio técnico de los IC los cuales se publican en el Catálogo Nacional de Indicadores (CNI).

## Características importantes
- Se incluyen scripts que utilizan bases de datos provenientes de Encuestas Nacionales de Gobierno (ENG) y Registros Administrativos descargados desde los microdatos.
- Para los IC basados en encuestas, se desarrolló una función en R que permite colorear automáticamente las estimaciones según su coeficiente de variación, facilitando así la
  interpretación de la confiabilidad de los datos al exportar los tabulados.

## Contenido del repositorio

1. `Compendio códigos IC_CNI_INEGI_VF.RMD`: archivo principal en R Markdown que contiene la sintaxis utilizada para el cálculo de los IC.
2. `Compendio códigos IC_CNI_INEGI_VF.pdf`: versión en PDF del archivo anterior, lista para entrega o difusión.
3. Carpeta `IMAGENES`: incluye las imágenes utilizadas en el documento.
4. Carpeta `Estimaciones`: contiene los tabulados generados desde R en formato `.xlsx`.

Información de contacto Autora:Martha Aguilar Jiménez, Correo electrónico:martha.aguilar@cimat.mx
