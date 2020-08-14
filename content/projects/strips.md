---
title: "Strips"
date: 2020-08-13T18:54:12+02:00
draft: true
---

### Strips

------------


El algoritmo de “strips” consiste en obtener un resultado meta, para alcanzar este estado se deberán alcanzar otros sub-estados en primer lugar. De esta manera, se obtiene una solución adecuada a nuestro problema, pero esto no quiere decir que sea la óptima. Strips solamente garantiza que la solución es viable.Hemos aplicado este algoritmo en el proyecto, funcionando correctamente. Para realizar este algoritmo nos hemos basado en el trabajo que hicimos en clase en C# de strips, y para hacer el modelo de datos nos basamos en lo que hicimos en clase el ultimo dia.

------------

#### ALGORITMOSTRIPREGRESIVO
Hemos conseguido aplicar una variante delalgoritmo de “Strips” en el proyecto. Para hacer este  algoritmo  obteníamos  el  estado  final,  y  a  partir  de  las  precondiciones  necesarias, construíamos el camino plan.El pseudocódigo del algoritmo que hemos aplicado es el siguiente:Obtenemos estado Meta del array de operacionesOrdenamos las precondiciones por el número de (sub)precondiciones que tenganFuncionaplicar operador(operacion){For(pcen operacion.precondiciones)Opc= Buscamos en la lista de operaciones, la pcAplicar_operador(opc)If(PlanActual no contiene operacion)Añadimos operación a planActual}

------------

>El proyecto fue realizado en Unity.

------------


[github](https://github.com/JorgeBarcena3/Strips-algorithm-IA "github")
