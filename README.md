##  **Presentacion de problema** 

## 🏥 **Estancia hospitalaria** 🏥

La hospitalización, o estancia hospitalaria, cuando es prolongada constituye una preocupación a nivel mundial debido a sus efectos negativos en el sistema de salud, aumentando los costos, generando deficiencia en la accesibilidad de prestación de servicios de salud, saturación de unidades de hospitalización y urgencias, por consiguiente, mayores efectos adversos como lo son las enfermedades intrahospitalarias.

El estudio de los procesos de atención en salud, así como el conocimiento de las características y perfiles de los usuarios con el objetivo de predecir la ocupación hospitalaria, es uno de los aspectos al que las autoridades de salud han prestado gran interés, pues permite no sólo garantizar los recursos necesarios para la atención del paciente, sino realizar ajustes respecto a la oferta y demanda de los servicios de salud y los implementos asociados.
​
## **Descripción del problema**

Un importante Centro de Salud lo ha contratado con el fin de poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados. 

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días. Por lo que debe generar dicha variable categórica y luego categorizar los pacientes según las variables que usted considere necesarias, justificando dicha elección. 
​
## **Modo de resolucion**

Para este problema se eligio un modelo simple(Arbol de decisiones)
Despues de hacer un analisis del Dataset train, se aprecio que la variedad de los datos por columna es baja, por lo que
elegir un modelo simple de clasificacion para entrenar y predecir seria lo mas ideal.

## **Pensamientos que se tuvieron en cuenta**

Como la salud de los pacientes que ingresan a un hospital es muy complejo, al momento de hacer ETL y EDA se tuvo en cuenta que aunque alguna variable podria llegara a parecer no util para el entrenamiento, se lo dejo intacto. Debido a que el dataset no provee informacion del pacieinte durante la estadia, unicamente de cuando ingresan. Toda la informacion resulta util.