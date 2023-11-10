# Reto 2. Extracción de tablas en un HTML

Ahora es momento de realizar la extracción de una tabla desde un html, realiza este reto desde tu RStudio Desktop. 

En este enlace se muestran los sueldos para _Data Scientists_ 

En este enlace [glassdoor](https://www.glassdoor.com.mx/Sueldos/data-scientist-sueldo-SRCH_KO0,14.htm), se muestran los sueldos para _Data Scientists_, realiza las siguientes acciones:

- Recuerden iniciar sesión en la página para que puedan hacer la extracción, sino les dará el error 403 o 404. 
- Extraer la tabla del HTML
- Si gustan pueden hacerlo en google colab  o en Rstudio cloud y luego guardarlo en su github
  https://colab.research.google.com/
  
- Quitar los carácteres no necesarios de la columna sueldos (todo lo que no sea número), para dejar solamente la cantidad mensual (Hint: la función `gsub` podría ser de utilidad, además ten cuidado con los carácteres especiales)

- Asignar ésta columna como tipo numérico para poder realizar operaciones con ella

Ahora podrás responder esta pregunta: ¿Cuál es la empresa que más paga y la que menos paga?
