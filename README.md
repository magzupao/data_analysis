#####################################################################  
Grupo de trabajo:    
- Roger Carhuatocto  
- Guido Portalanza  
- Marco Guado  
  
Mayo 2021  
Barcelona, ESPAÑA  

#####################################################################  
  
# Objetivo:
Analizar el set de datos de los proveedores de protección personal por COVID 19 - MINSA, PERU.  

# Recurso:  
Origen de datos que se analizara:  
´´´  
https://www.datosabiertos.gob.pe/dataset/distribuci%C3%B3n-de-equipos-de-protecci%C3%B3n-personal-por-covid-19-ministerio-de-salud-minsa-0#{view-grid:{columnsWidth:[{column:!FECHA,width:154},{column:!RUC,width:188},{column:!PROVEEDOR,width:374},{column:!PRODUCTO,width:314},{column:!CANTIDAD,width:119}]}}  
´´´
  
# Tareas a ejecutar:  
- Crear un script que analice el dataset y que pueda extraer los RUC y almacenarlo en una lista.  
- La lista con todos los RUC almacenados se utilizar para consultar en la SUNAT, con esto obtendremos los datos de las empresas como:
tipo de sociedad, quienes conforman la empresa, fecha de creacion, reputacion etc.
- Automatizar la consulta de los RUC usando la API de la SUNAT.
