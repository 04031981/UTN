<Div align="center">
    <img src="https://i.postimg.cc/3Rbr23nJ/UTN-Logo.png="Texto alternativo" style="width: auto; height: 100%;"/>
</div>


<p align="center"><span style="color:White; font-size: 40px;">Probabilidad</span></p>


---
###### [Ver Arte 2D](../Arte/2D.md)
###### [Ver Diseño de Videojuegos](../Diseño/VJ.md)
###### [Ver Probabilidad](../Probabilidad/Probabilidad.md)
###### [Ver Documentación](../Documentacion/Arquitectura.md)
###### [Ver Programación](../Programacion/Programacion.md)


### Tabla de Contenidos

---

- [Probabilidad](#probabilidad)
    - [Definiciones básicas](#definiciones-básicas)
- [Estadística](#estadística)
    - [Definiciones básicas](#definiciones-básicas-1)
- [Unidad 1](#unidad-1)
  - [Introducción a la teoría de la probabilidad](#introducción-a-la-teoría-de-la-probabilidad)
    - [Probabilidad: definiciones básicas](#probabilidad-definiciones-básicas)
    - [Espacio muestral](#espacio-muestral)
      - [Finitos](#finitos)
      - [Infinitos](#infinitos)
    - [Reglas de conteo (Espacio muestral)](#reglas-de-conteo-espacio-muestral)
      - [Combinaciones](#combinaciones)
      - [Permutaciones](#permutaciones)
      - [Variaciones](#variaciones)
  - [Historial de Versiones](#historial-de-versiones)

---

# Probabilidad

[Inicio](#tabla-de-contenidos)

### Definiciones básicas


- La probabilidad es el 
cálculo matemático que 
evalúa las posibilidades 
que existen de que una 
cosa suceda cuando 
interviene el azar.

# Estadística
### Definiciones básicas
- La estadística es una disciplina científica que se 
ocupa de la obtención, orden y análisis de un conjunto 
de datos con el fin de obtener explicaciones y 
predicciones sobre fenómenos observados.


# Unidad 1

## Introducción a la teoría de la probabilidad

### Probabilidad: definiciones básicas

- Experimento determinístico: 
  Un experimento determinístico es un experimento que realizado siempre en las mismas condiciones produce un mismo resultado.

- Experimento aleatorio: Un experimento aleatorio es aquel que realizado en las mismas condiciones puede dar resultados diferentes.



### Espacio muestral
El conjunto de todos los resultados que pueden salir en un experimento aleatorio es el espacio muestral de ese experimento aleatorio. A cada elemento del conjunto podemos denominarlo 
PUNTO muestral


#### Finitos 

Un espacio muestral es 
finito si contiene un 
número finito de 
resultados



#### Infinitos

- Un espacio muestral 
infinito continuo tiene un 
número infinito de 
resultados que no son 
numerables (pueden ser 
cualquier valor dentro de un 
intervalo)
- Un espacio muestral infinito 
discreto tiene un número 
infinito de resultados que 
son numerables (pueden 
ser listados en una 
secuencia)


### Reglas de conteo (Espacio muestral)


#### Combinaciones
Orden no importa. Hay subconjuntos.
- Con repetición :
Dado un conjunto de n elementos distinguibles, 
se llama combinación con repetición de
x elementos escogidos entre los n a cualquier 
colección de x elementos del conjunto, con 
repeticiones eventuales de algunos de ellos.


$$
CR(n, x) = \binom{n+x-1}{x} = \frac{(n+x-1)!}{x!(n-1)!}
$$


- Sin repetición: Dado un conjunto de n elementos distinguibles, 
se llama combinación sin repetición de
x elementos, con x < n, elegidos entre los n, a 
cualquier subconjunto de x elementos distintos 
del conjunto.
​
$$C(n, x) = \binom{n}{x} = \frac{n!}{x!(n-x)!}$$






#### Permutaciones
Orden importa. No hay subconjuntos.
- Con repetición: Las permutaciones con repetición se refieren a 
las distintas maneras en que se pueden ordenar
n elementos donde algunos de ellos pueden
repetirse algunas veces.

$$
P\left(\begin{array}{c}n \\ r\end{array}\right) = \frac{n!}{a! \cdot b! \cdot \ldots \cdot r!}
$$

- Sin repetición: Las permutaciones sin repetición se refieren a las 
distintas maneras en que se pueden ordenar
𝑛 elementos únicos. En este caso, cada elemento 
solo puede aparecer una vez en cada ordenación.

$$
P(n) = n!
$$



#### Variaciones
Orden importa. Hay subconjuntos.

- Con repetición:  Dado un conjunto de n elementos
distinguibles, se llama variación con repetición de 
r elementos elegidos entre los n a cualquier 
disposición ordenada, con repeticiones 
eventuales, de m elementos del conjunto. En este 
caso r puede ser mayor o igual que n

$$
VR (n, r) = n^r
$$

- Sin repetición: Definición: Dado un conjunto de n elementos
distinguibles, se llama variación sin repetición de p
elementos, con p < n, elegidos entre los n, a cualquier 
disposición de p elementos distintos del conjunto.

$$
V(p, n) = \frac{n!}{(n-p)!}
$$


















---

## Historial de Versiones

[Inicio](#tabla-de-contenidos)

Fecha       | Versión | Autor                 | Organización | Descripción
------------|---------|-----------------------|--------------|------------
10/08/2024  | 01      | Dario Cano Valdegaray | Uso Personal | Probabilidad