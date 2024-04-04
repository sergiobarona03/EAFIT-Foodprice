# Bases de datos - Foodprice

El objetivo de este repositorio es presentar los insumos empleados en la construcción y la implementación del paquete ‘Foodprice’ version 1.0.0. El repositorio contiene los siguientes insumos:

#

1. **Bases de datos de ejemplo (estructuras generales):** estas bases de datos muestran las estructuras necesarias para el correcto funcionamiento del paquete, utilizando grupos y alimentos arbitrarios como referencia. Los cojuntos de datos presentados en la carpeta son los siguientes:

- data_example: Conjunto de datos de insumo a los modelos, este comprende 96 alimentos (filas) y 24 variables (columnas) correspondientes a los precios, intercambios, grupos, subgrupos y contribuciones nutricionales de cada alimento.
   
- EER_example: Conjunto de datos de ejemplo que contiene los requisitos energéticos para grupos demográficos arbitrarios. *(Necesario para CoCA)*
   
- UL_example: Conjunto de datos con los requerimientos máximos para varios nutrientes en diferentes grupos demográficos arbitrarios diferenciados según el sexo. *(Necesarios para CoNA)*
   
- EER_LL_example: Conjunto de datos de ejemplo con los requerimientos energéticos y requerimientos mínimos para varios nutrientes en grupos demográficos y sexos arbitrarios. *(Necesarios para CoNA)*
   
- serv_example: Conjunto de datos que incluye los requisitos de intercambio para alimentos y subgrupos arbitrarios. *(Necesario para CoRD)*
   
- diverse_example: El conjunto de datos incluye la cantidad de alimentos a seleccionar por subgrupos. *(Necesario para CoRD)*

#   
   
2. **Insumos nacionales:** incluye bases de datos de requerimientos estimados a nivel nacional. Además, se encuentra una base de datos llamada "data_Medellin", que representa la estimación de precios minoristas y los alimentos disponibles con su composición nutricional que realiza "Foodprice 1.0.0" para la ciudad de Medellín en el mes 11 y año 2023.

- La denominación de los requerimientos nacionales sigue la misma lógica expresada en el punto anterior (1).

#

3. **Insumos locales (caso de estudio: Cali):** incluye las bases de datos empleadas en la aplicación de la metodología para el caso de Cali, Colombia, en el período de septiembre/2022. Para el lugar y período de estudio, las bases de datos utilizadas fueron las siguientes:

- abs_cavasa: información primaria de abastecimiento de alimentos proporcionada por CAVASA (flujo de carga en toneladas)
  
- abs_cali: base de datos de abastecimiento (flujo de carga en kg) para la ciudad de Cali, integrando la información secundaria extraída de SIPSA y la información primaria de CAVASA.
  
- precios_cavasa: información primaria de precios medios (semanales y mensuales) de alimentos proporcionada por CAVASA (la unidad de referencia cambia según la unidad comercial).
  
- precios_sipsa: información secundaria sobre el precio promedio mensual de los alimentos (precio/kg) extraído de SIPSA.
  
- TCAC: base de datos sobre la composición nutricional de los alimentos según la Tabla de Composición de Alimentos Colombianos
  
- TCAC_grupos: mapeo entre la clasificación de la TCAC y los grupos de alimentos de las Guías Alimentarias Basadas en Alimentos (GABA) para la población colombiana.
  
- mapeo_cavasa: mapeo entre el nombre de los alimentos de las bases de datos de precios y abastecimiento proporcionadas por CAVASA (CAVASA no emplea una clasificación por códigos y, en consecuencia, el mapeo es realizado de acuerdo con el nombre del alimento).
  
- mapeo_sipsa_abs_precios: mapeo entre el nombre de los alimentos de las bases de precios y abastecimiento de SIPSA (el mapeo opera por el nombre del alimento y no emplea el código TCAC).
  
- mapeo_tcac: mapeo entre la lista de alimentos (incluyendo SIPSA y CAVASA) y la composición nutricional de la TCAC.
  
- DRI_m y DRI_f: requerimientos de energía y nutrientes esenciales para el sexo masculina y femenina, respectivamente.
 
- EER_share_m y EER_share_f: recomendaciones proporcionadas por GABA (diferenciadas según grupos de alimentos) para el sexo masculino y femenino, respectivamente.
  
- intercambios: base de datos con el peso (expresado en gramos) de un intercambio para cada alimento.
 
   
   
