##  **Presentacion de problema** 

## 馃彞 **Estancia hospitalaria** 馃彞

La hospitalizaci贸n, o estancia hospitalaria, cuando es prolongada constituye una preocupaci贸n a nivel mundial debido a sus efectos negativos en el sistema de salud, aumentando los costos, generando deficiencia en la accesibilidad de prestaci贸n de servicios de salud, saturaci贸n de unidades de hospitalizaci贸n y urgencias, por consiguiente, mayores efectos adversos como lo son las enfermedades intrahospitalarias.

El estudio de los procesos de atenci贸n en salud, as铆 como el conocimiento de las caracter铆sticas y perfiles de los usuarios con el objetivo de predecir la ocupaci贸n hospitalaria, es uno de los aspectos al que las autoridades de salud han prestado gran inter茅s, pues permite no s贸lo garantizar los recursos necesarios para la atenci贸n del paciente, sino realizar ajustes respecto a la oferta y demanda de los servicios de salud y los implementos asociados.
鈥?
## **Descripci贸n del problema**

Un importante Centro de Salud lo ha contratado con el fin de poder predecir si un paciente tendr谩 una estancia hospitalaria prolongada o no, utilizando la informaci贸n contenida en el dataset asociado, la cual recaba una muestra hist贸rica de sus pacientes, para poder administrar la demanda de camas en el hospital seg煤n la condici贸n de los pacientes recientemente ingresados. 

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado m谩s de 8 d铆as. Por lo que debe generar dicha variable categ贸rica y luego categorizar los pacientes seg煤n las variables que usted considere necesarias, justificando dicha elecci贸n. 
鈥?
## **Modo de resolucion**

Para este problema se eligio un modelo simple(Arbol de decisiones)
Despues de hacer un analisis del Dataset train, se aprecio que la variedad de los datos por columna es baja, por lo que
elegir un modelo simple de clasificacion para entrenar y predecir seria lo mas ideal.

## **Pensamientos que se tuvieron en cuenta**

Como la salud de los pacientes que ingresan a un hospital es muy complejo, al momento de hacer ETL y EDA se tuvo en cuenta que aunque alguna variable podria llegara a parecer no util para el entrenamiento, se lo dejo intacto. Debido a que el dataset no provee informacion del pacieinte durante la estadia, unicamente de cuando ingresan. Toda la informacion resulta util.