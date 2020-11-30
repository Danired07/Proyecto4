---

## Universidad de Costa Rica
### Escuela de Ingeniería Eléctrica
#### IE0405 - Modelos Probabilísticos de Señales y Sistemas

Segundo semestre del 2020

---

* Estudiante: **Daniel Quesada Valverde**
* Carné: **B65592**
* Grupo: **1**

---



En el código 4.1 los principales cambios que se hicieron fueron en las funciones, se creó una función de modulador para la señal T y otro para la señal Q. En estos dos los principales cambios que hay de una con respecto a la otra, fue que, para la variable portadora, en la señal I se definido por medio de la función coseno, por otro lado, la variable portadora Q, se definido por medio de la función seno. Luego de esto, se creó una función Suma_senal_Tx, se realizó la suma de las señales respectivas para cada Tx, y se obtuvo un Tx a partir de ellas. En la función demodulador, se crearon 3 vectores para los bits obtenidos de I y Q, además de uno para Rx, el cual se hizo con el doble de la dimensión que los anteriores.  Además de esto, se hizo un if que seleccionara dependiendo los valores de energía si es mayor a cero les asigna un uno a bits_RxI y bits_RxQ.  De lo contrario, se les asigna un cero. Se crearon 3 vectores para los bits obtenidos de I y Q, además de uno para Rx, el cual se hizo con el doble de la dimensión que los anteriores. Por último, se procedió a realizar las gráficas respectivas, excluyendo la de moduladora que venía originalmente.

En el código 4.2, se reutilizó en gran parte de este el código empleado en el laboratorio 4, para las pruebas de estacionariedad y ergodicidad. Los cambios más relevantes que se realizaron fueron que en este código se trabajan con las variables aleatorias de tipo Bernoulli. Luego de esto, se hizo un if que le otorgara el valor de -1 a las variables aleatorias que fueran cero, tanto las de X, como las de Y. Además de esto se calcularon los valores esperados teóricos, y se compara con el valor esperado de la señal modulada.

Análisis 4.2:
Según los datos que nos brinda la gráfica, se puede comprobar como el valor esperado teórico si coincide con el valor esperado de la señal modulada. La cual como se puede apreciar en el eje vertical igual a cero, es constante.  Se puede comprobar que la señal es estacionaria en sentido amplio, ya que presenta cambios en sus propiedades estadísticas con el pasar del tiempo. En cuanto a la ergodicidad, sabemos que en esta se establece una igualdad entre el promedio estadístico y el promedio temporal, en un proceso aleatorio, esto nos queda más claro con los datos en nos brinda la gráfica.

En el código 4.3, se obtuvo del video proporcionado por el profesor, aquí se obtuvo la densidad espectral de la potencia para la senal_Tx, con base en los datos obtenidos en las partes anteriores, por lo cual, solo fue realizar cambios pequeños en las variables.  En esta gráfica destaca el punto más alto a los 5KHZ.

