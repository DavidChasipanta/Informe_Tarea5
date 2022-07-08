# Informe_Tarea5
# **1.OBJETIVOS**

**Objtivo  General**

Explicar y resolver los problemas presentados en los capítulos nueve y diez del libro "Principios de circuitos eléctricos" de Floyd mediante el uso de los conocimientos adquiridos en clases y el contenido del libro referente al desarrollo de ecuaciones simultaneas para encontrar un voltaje y las corrientes en el análisis de un circuito eléctrico de manera ágil, permitiéndonos identificar las características correspondientes y lograr resolver cualquier tipo de circuito con un análisis y razonamiento adecuado.

**Ojetivo Especifico**

* Identificar de una manera concreta las incognitas, resolver los circuitos mediante los los metodos de mallas y nodos para hallas los valores de las corrientes y voltajes correspondientes.

* Analizar de forma correcta los resultaos obtenidos, establecer la relación de los componentes en un simulador virtual y corroborar los resultados obtenidos de formateórica.

* Establecer los diferentes conocimientos sobre los campos magneticos, sus componentes y caracteristicas dentro de elementos.

# **2.MARCO TEÓRICO**

![image](https://user-images.githubusercontent.com/105617383/177857919-35977d11-95c8-4caf-ad22-7210187dbb9b.png)

# **3.Explicación y resolución de ejercicios**

**PROBLEMAS**

**2. Evalúe cada determinante:**

(a) (4 * 3)-(2 * 6) = 0

(b) (9 * 5)-(0) = 45

(c) (12 * (-1))-((-2) * 15) = 18

(d) ((-20) * 100)-(30 * 50) = -3500

**4. Evalúe cada uno de los determinantes:**

![image](https://user-images.githubusercontent.com/105617383/177885644-da5539b1-9bbc-4378-ab9a-2cd03822bf50.png)

a) -10+16 = 6

b) (3 - 0.15 + 0.024 - 0.096 + 0.225 + 0.5) =3,503

**6. Determine I3 en el ejemplo 9-4.**

![image](https://user-images.githubusercontent.com/105617383/177886861-b7a61c0d-186e-4bf1-8ffe-810db40e3df7.png)

Formando un determinante se obtiene: (0 + 3 + 0.15) - (0 + 0.8 + 0) = 3.15 - 0.8 = 2.35

![image](https://user-images.githubusercontent.com/105617383/177887038-c2eaad54-4727-438f-bb11-b5f7030c1cc4.png)

**8. Determine V1, V2, V3 y V4 resolviendo el siguiente conjunto de ecuaciones con una calculadora:**

![image](https://user-images.githubusercontent.com/105617383/177886405-32c4a06c-dd41-4533-b9ea-9b7f49815c81.png)

![image](https://user-images.githubusercontent.com/105617383/177887369-7695abac-7ca9-4094-9add-70fd37f05b23.png)
![image](https://user-images.githubusercontent.com/105617383/177887451-1bdae552-c81b-4817-a023-114d5fa7260c.png)

**10. Resuelva las tres ecuaciones simultáneas del problema 7 con su calculadora.**

![image](https://user-images.githubusercontent.com/105617383/177887590-9bd95231-7091-485e-9ae4-b430b9b5ab25.png)

**SECCIÓN 9-2 Método de la corriente en ramas**

**12. Resuelva para cada una de las corrientes de rama ilustradas en la figura 9-26**

![image](https://user-images.githubusercontent.com/105617383/177887782-56b7cab9-4285-49f1-9716-35ef50b48c16.png)

Sistema de Ecuaciones

(8.2) I2 + 10I2-12= 0 (1)

10I2 + (5.6) I3 - 6 = 0 (2)

Nodo A

0 = I1 - I2 - I3

I1 = I2 + I3 (3)

Reemplazamos la ecuación (3) en la ecuación (1)

(8.2) (I2 + I3) + 10I2 = 12

(18.2) I2 + (8.2) I3= 12 (4)

Despejamos la ecuación (2)

I2 = 6 - 5.6 I3 / 10 

Remplazamos I2 en la ecucación (4)

![image](https://user-images.githubusercontent.com/105617383/177903381-0158a50d-0de9-46be-9e7d-df05afddb8b8.png)

**14. Determine la corriente a través de cada resistor mostrado en la figura 9-27.**

![image](https://user-images.githubusercontent.com/105617383/177887983-23f6e5f7-63f6-4e11-b3ca-14e4d733cb97.png)

La corriente Is es la misma que pasa R3

Is = IR3 = 100 mA

Se deduce que la corriente que entra es la misma que sale por lo tanto I1 = 100mA

I2 = (100 / 147)(100) = 68.03mA

**SECCIÓN 9-3 Método de la corriente en lazos**

**16. Escriba el determinante característico para las ecuaciones:**

0.045IA + 0.130IB + 0.066IC = 0  → 0.177IA + 0.0420IB + 0.109IC = 12  → 0.078IA + 0.196IB + 0.029IC = 3.0

Solución

![image](https://user-images.githubusercontent.com/105617383/177903618-aaf47360-c6b8-4c4c-9618-9b3658ebd7cc.png)

**18. Determine las corrientes de rama en la figura 9-28.**

![image](https://user-images.githubusercontent.com/105617383/177888593-9e816bc5-7a29-4047-aff5-578291b7c6b9.png)

![image](https://user-images.githubusercontent.com/105617383/177888573-2c0124e7-ea37-4deb-8c26-f558781dae7e.png)

**20. Escriba las ecuaciones de lazo para el circuito de la figura 9-29.**

![image](https://user-images.githubusercontent.com/105617383/177888626-d0fae40b-03ba-442d-85fa-64939d3b987f.png)

LasoA: 7IA + 10(IA - IB) = 1.5

LasoB: 10(IB - IA) + 27IB + 4.7(IB - IC) = 3

LasoC: -4.7(IC - IB)+15IC = 1.5

**22. Determine la corriente a través de cada resistor en la figura 9-29.**

![image](https://user-images.githubusercontent.com/105617383/177890596-fb17f5bb-4b04-461a-ad30-6ed3164e8902.png)

LasoA: 7IA + 10(IA - IB) = 1.5

LasoB: 10(IB - IA) + 27IB + 4.7(IB - IC) = 3

LasoC: -4.7(IC - IB)+15IC = 1.5

La corriente son:

IA = 1.5mA

IB = 0.16mA

IC = 0.12mA

**24. Cuando se conecta un resistor de 10 kÆ desde la terminal A hasta la terminal B en la figura 9-30, ¿cuál
es la corriente que circula a través de él?**

![image](https://user-images.githubusercontent.com/105617383/177890613-047ebe88-2dc2-40fd-b00d-59c41ad2d7ce.png)

![image](https://user-images.githubusercontent.com/105617383/177904873-51c8fe8a-c2c5-4005-b254-74606ddc1312.png)

![image](https://user-images.githubusercontent.com/105617383/177904737-8396db2a-99f5-4978-b9fe-524c7a447cd2.png)

![image](https://user-images.githubusercontent.com/105617383/177904762-5053d8f6-24d0-46ec-93a5-5213c120e6be.png)

![image](https://user-images.githubusercontent.com/105617383/177904784-5105e187-a2c7-4272-8727-f7dd2b2403db.png)

**SECCIÓN 9-4 Método del voltaje en nodos**

**26. En la figura 9-32, use el método del voltaje en nodos para determinar el voltaje presente en el punto A
con respecto a tierra.**

![image](https://user-images.githubusercontent.com/105617383/177890462-83ed7bae-0bf8-4e56-b93a-e72c5934224d.png)

![image](https://user-images.githubusercontent.com/105617383/177891908-8fa1c5b2-a406-4765-ac2a-fb84333bf3d0.png)

I1-I2-I3=0

Usando leyes de Ohm

30-Va/82 – Va-40/68 – Va/147 =0

30/82 – Va/82 – Va/68 + 40/68 – Va/147 = 0

(9996(30)-9996Va-12054Va+12054(40)-5576Va) /819672=0

782040-27626Va = 0

Va = 782040/27626

Va = 28.3 V

**28. Escriba las ecuaciones de voltaje de nodo para la figura 9-29. Use su calculadora para determinar los
voltajes de nodo.**

![image](https://user-images.githubusercontent.com/105617383/177890485-38dd1c3f-0638-47cc-a3c2-2646b7e001e4.png)

I1 – I2 – I3 =0 (1)

I3 + I4 – I5 = 0 (2)

Sustituir las leyes de ohm en 1

1.5- Va / 47 – Va/10 – (Va -Vb) /27= 0

1.5/47 – Va/47 – Va/ 27 + Vb /27 = 0

-270Va – 1269 Va – 470Va / 12690 + Vb /27 = -1.5 / 47

2009 Va /12690 – Vb /27 = 1.5/47

0.158 Va – 0.037 Vb = 0.0319

Sustituir leyes de ohm en 2

(Va – Vb) /27 +( 3-Vb) / 4.7 – (Vb -1.5) /15 =0

Va/27 – Vb/27 + 3 / 4.7 – Vb / 4.7 – Vb / 15 + 1.5 /5 =0

0.037 Va – 0.317Vb = -0. 738

Sistema de ecuaciones

0.158 Va – 0.037Vb = 0.0319 0.037Va – 0.317 Vb = -0.738

Va = 2.4177 V Vb = 0.768 V

**30. Determine el voltaje en los puntos A, B y C en la figura 9-34.**

![image](https://user-images.githubusercontent.com/105617383/177890502-e46334de-c7b1-4d41-841f-6aac61dd4799.png)

![image](https://user-images.githubusercontent.com/105617383/177892360-49e35169-9887-432c-86ae-05771e878c92.png)
![image](https://user-images.githubusercontent.com/105617383/177892377-08cca953-6e7f-4575-97c5-f74429aa5efc.png)

**CAPITULO 10**

**PROBLEMAS**

**SECCIÓN 10-1 El campo magnético**

**2. En cierto campo magnético, el área de sección transversal es de 0.5 m^2 y el flujo es de 1500 μWb. ¿Cuál es la densidad de flujo?**

![image](https://user-images.githubusercontent.com/105617383/177889891-b90e363b-a59a-4d2e-922b-9b3150096b56.png)

**4. En un lugar dado, suponga que el campo magnético terrestre es de 0.6 gauss. Exprese esta densidad de flujo en teslas.**

![image](https://user-images.githubusercontent.com/105617383/177905219-18100bfe-cd83-4ec8-a2df-82ebe852e738.png)

**SECCIÓN 10-2 Electromagnetismo**

**6. ¿Qué le sucede a la aguja de la brújula mostrada en la figura 10-9 cuando la corriente que circula a través del conductor se invierte?**

![image](https://user-images.githubusercontent.com/105617383/177889930-49f59ff7-c928-4570-9b3e-81af339fd51d.png)

* Si la corriente que pasa por el conductor se invierte, la rotación de las líneas de fuerza también se invertirían por ende la brújula llegaría a mostrar el lado opuesto.

**8. Determine la reluctancia de un material con longitud de 0.28 m y área de sección transversal de 0.08 m^2 si la permeabilidad absoluta es de 150 x 10^(-7) Wb/At*m.**

![image](https://user-images.githubusercontent.com/105617383/177890018-549c6867-a73d-476e-941a-5fb23a876d53.png)

**SECCIÓN 10-3 Dispositivos electromagnéticos**

**10. De manera característica, cuando se activa un solenoide, ¿se extiende o retrae el émbolo de imán?**

![image](https://user-images.githubusercontent.com/105617383/177890146-fafcfedb-4e27-420a-9f76-42ab11013d40.png)

-Cuando se llega a energizar un solenoide el émbolo de imán se llega a retraer, como se ve en la figura.

**12. Explique la secuencia de los eventos mostrados en el circuito de la figura 10-43 comenzando cuando el interruptor 1 (SW1) se cierra.**

![image](https://user-images.githubusercontent.com/105617383/177890188-0497bf1b-b0db-4c37-a62c-4f458d23e343.png)

* El circuito esta alimentado por una fuente de voltaje, y si el interruptor 1 (SW1) se cierra permite el paso de la corriente de la fuente hacia la bobina del relevador, la cual energiza el contacto que esta alimentado por 9V haciendo que se cierre y a su vez este ilumine las lámparas 1 y 2.

**SECCIÓN 10-4 Histéresis magnética**

**14. ¿Cuál es la fuerza magnetizante en el problema 9 si la longitud del núcleo es de 0.2 m?**

![image](https://user-images.githubusercontent.com/105617383/177890242-67aa2ceb-8381-424d-a648-45fe8a54ecd8.png)

**16. En la figura 10-44, hay 500 vueltas. Determine**

**(a) H (b) ∅ (c) B**

![image](https://user-images.githubusercontent.com/105617383/177890269-1d4a6ba1-4691-42d2-b414-9237030838e3.png)

**(a) H**

H = Fm/l

H= 500(0.25A) /(0.30Mm)

H= 416 At/m

**(b) ∅**

R= l/micra A

R= 0.30m /250 micra (0.30mx0.02m)

R= 200x10^3 At/Wb

ɸ = Fm/R

ɸ= 500(0.25A)/ 200x10^3 At/Wb

ɸ=6.25X10^(-4)

**C) B = ɸ/ A**

B= 6.25X10^(-4)/ (0.30mx0.02m)

B= 0.1041

**SECCIÓN 10-5 Inducción electromagnética**

**18. De acuerdo con la ley de Faraday, ¿qué le sucede al voltaje inducido en una bobina dada si la razón de cambio del flujo magnético se duplica?**

* Si la razón de cambio del flujo magnético se duplica, el voltaje inducido en la bobina también se duplicará, ya que según la ley de Faraday, el voltaje inducido en una bobina es directamente proporcional a la rapidez de cambio del campo magnético.

**20. Un campo magnético cambia a razón de 3500 x 10^(-3) Wb/s. ¿Cuánto voltaje se induce en una bobina de 500 vueltas colocada en el campo magnético?**

![image](https://user-images.githubusercontent.com/105617383/177889479-a01b9323-d18a-406b-97e2-ead10f2f4aa3.png)

**SECCIÓN 10-6 Aplicaciones de la inducción electromagnética**

**22. En la figura 10-33, ¿por qué no se induce voltaje cuando el disco no está girando?**

![image](https://user-images.githubusercontent.com/105617383/177889526-4e7654b9-2bb7-42bb-9c44-42bd241573f7.png)

* No produciría voltaje ya que el apéndice de acero o diente saliente no pasa por el entrehierro del imán, entonces al no producir un campo magnético cambiante, no hay voltaje inducido.

**24. Un generador de cd básico de una espira gira a 60 rev/s. ¿Cuántas veces cada segundo llega el voltaje de cd de salida a su pico (alcanza un máximo)?**

* Como una rotación tiene cuatro posiciones, entonces el voltaje de cd de salida llega 15 veces cada segundo a su pico alcanzando un voltaje máximo.

# **4.VIDEO**

https://youtu.be/WalCNJBIx0Y

# **5.CONCLUCIONES**

* El presente analisis permitio aplicar los metodos ya conocidos de resolucion de circuitos electricos de practicas anteriores, otrogo resultados confiables ya que fueron simulados, cada circuito reporto valores como resistencia total o corrientes en cada componente de dicho circuito para permitir obtener resultados y un analisis correcto, por lo tanto llegamos a comprender de una manera el funcionamiento del tema.

# **BIBLIOGRAFÍA**

Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.
