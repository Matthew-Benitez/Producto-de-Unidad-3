# ANÁLISIS DE FUENTE Y CARGA TRIFÁSICAS
1.  OBJETIVOS
    - Objetivo General:
      - Comprender los diferentes tipos de conexiones entre cargas y generadores.
    - Objetivos Específicos:
      - Conocer las cuatro configuraciones de fuente y carga.
      - Aprender a determinar los tipos de voltaje que se encuentran en las configuraciones de fuente y carga.
      - Aprender a determinar los tipos de corriente que se encuentran en las configuraciones de fuente y carga.
      
2. MARCO TEÓRICO

![0001 (11)](https://user-images.githubusercontent.com/76133212/112942916-6c675d00-90f6-11eb-9df7-45cd58a3b6cb.jpg)
![0001 (12)](https://user-images.githubusercontent.com/76133212/112942922-6e312080-90f6-11eb-9b12-d33e9cb2469b.jpg)
![0001 (13)](https://user-images.githubusercontent.com/76133212/112942930-6f624d80-90f6-11eb-8124-31a45c347f2b.jpg)


3. DESARROLLO



4. LISTA DE COMPONENTES

![image](https://user-images.githubusercontent.com/75439689/109887556-f0d9d380-7c4f-11eb-9c05-1e1f932c03e3.png)

*Ejercicio 14 a)*

![image](https://user-images.githubusercontent.com/75439689/109887613-0949ee00-7c50-11eb-9072-a4000eb4b27c.png)

*Ejercicio 14 c)*

5. EXPLICACIÓN

   5.1.- El ejercicio a resolver es el 14 a) que nos pide hallar la impedancia Zl para tener la máxima transferencia de potencia, para ello primero calculamos la impedancia capacitiva que es 11.287 kΩ. Ahora tenemos la impedancia total del circuito que es: 6.8 - j1.128 kΩ. El teorema nos dice que para tener la transferencia de potencia máxima se necesita del complejo conjugado, es decir, para este ejercicio necesitamos en Zl una impedancia de 6.8 + j11.287 kΩ. Para lograr obtener esta impedancia Zl debe tener un resistor de 6.8 kΩ y un inductor con impedancia inductiva de 11.287 kΩ, para ello simplemente la calculamos con la formula de ImpedanciaInductiva=2πfL, donde despejamos L y tenemos que el inductor tiene un valor de 0.5988 H, que aproximándolo es un inductor de 0.6 H. Con estos valores procedemos a realizar nuestra simulación y comprobamos que con ese Zl obtenemos la áxima transferencia de potencia.
   
   5.2.- El ejercicio 15 c) consta de un inductor y un capacitor, para analizar este problema utilizamos el teorema de Thévenin y primero vemos que el inductor y el capacitor están en paralelo, para poder sacar una impedancia equivalente calculamos la impedancia inductiva y la capacitiva, dándonos como resultado Xc=60.286Ω y Xl=75.398Ω, ahora hacemos una suma en forma paralela de ambos y obtenemos que la impedancia es de 300.78Ω, la impedancia total nos da: 50 - j300.78, y para obtener la máxima transferencia de potencia utilizamos la conjugada de esta, es decir, necesitamos una impedancia de 50 + j300.78, en otras palabras, necesitamos en Zl un resistor de 50 Ω y un inductor con impedancia inductiva de 300.78Ω, para determinar el valor del inductor utilizamos la formula Xl=2πfL, y despejamos L, quedándonos un L de 0.4 H. Con estos valores procedemos a realizar nuestra simulación y comprobamos que con ese Zl obtenemos la áxima transferencia de potencia.
   
6. APORTACIONES

   6.1.1. Circuito 14 a)

![image](https://user-images.githubusercontent.com/75439689/109889063-a443c780-7c52-11eb-8bdd-f0c960168e36.png)

   6.1.2. Materiales del Circuito

![image](https://user-images.githubusercontent.com/75439689/109889231-f4228e80-7c52-11eb-926a-00f27227b7b6.png)

   6.1.3. Circuito Armado

![image](https://user-images.githubusercontent.com/75439689/109889301-14524d80-7c53-11eb-8b20-be4c48a3f660.png)

   6.1.4. Potencia Máxima del Circuito

![image](https://user-images.githubusercontent.com/75439689/109889352-35b33980-7c53-11eb-81d3-e9c3a4d8f86c.png)

   6.2.1. Circuito 14 c)

![image](https://user-images.githubusercontent.com/75439689/109889399-4d8abd80-7c53-11eb-998f-2153f46d7a54.png)

   6.2.2. Materiales del Circuito
 
![image](https://user-images.githubusercontent.com/75439689/109889535-8f1b6880-7c53-11eb-9f78-88742295d905.png)

   6.2.3. Circuito Armado

![image](https://user-images.githubusercontent.com/75439689/109889587-aa867380-7c53-11eb-9313-1ffbd5c22bd6.png)

   6.2.4. Potencia Máxima del Circuito

![image](https://user-images.githubusercontent.com/75439689/109889687-de619900-7c53-11eb-9b6f-59abf885730b.png)

7. Conclusiones

   - Las aplicaciones de los campos magnéticos en circuitos eléctricos es fundamental en el desarrollo de estos, ya que como se ha podido apreciar, gracias a las bobinas y su movimiento dentro de un campo magnético, se obtiene un generador con voltajes en fases distintas, lo que permite diversas fuentes de salida.

   - Los generadores trifásicos resultan más eficientes a la hora de aplicarse a diferencia de los generadores monofásicos. Esto debido a que los generadores trifásicos permiten un mayor valor de potencia total ya que consta de 3 diferentes conexiones (sin contar la conexion neutral que sería la cuarta), y por cada una existe una potencia dirigida a una carga. Además, los generadores trifásicos son mejores en la aplicación ya que permiten una menor consideración en lo que respecta la sección transversal del cable de cobre.

   - Existen cuatro tipos de sistemas entre generador y carga, las cuales dependen de su forma de conexión (ya sea en forma Y o en forma Δ). Pero cada uno de estos sistemas tiene sus respectivas funciones las cuales dependen de lo que se desea aplicar, Por ejemplo si se desea que la corriente que legue a una carga sea igual a la corriente de fase y que esta no disminuyas, se debe aplicar un sistema Y-Y, ya que este permite que se dé esto gracias a sus características.



8. Bibliografía

   - Floyd, T.L.(2007). *Principios de circuitos eléctricos* (Octava ed.)
