# Ejemplos de la Ley de los Grandes Números

## Ejemplo 1: Lanzamiento de un dado justo

- **Variable aleatoria:** resultado de lanzar un dado de 6 caras.  
- **Valores posibles:** $1, 2, 3, 4, 5, 6$  
- **Valor esperado:**
$$
\mathbb{E}[X] = \frac{1+2+3+4+5+6}{6} = 3.5
$$

 En la simulación, lanzamos el dado muchas veces y calculamos el **promedio acumulado**.  
 A medida que aumentamos el número de lanzamientos, ese promedio **se aproxima a 3.5**, cumpliendo la LGN.

---

##  Ejemplo 2: Números aleatorios en $[0,1]$

- **Variable aleatoria:** número generado de forma uniforme entre 0 y 1.  
- **Valor esperado:**
$$
\mathbb{E}[X] = \int_0^1 x \, dx = 0.5
$$

 En la simulación, generamos muchos números aleatorios uniformes y calculamos su **promedio acumulado**.  
 Con más muestras, el promedio **se acerca a 0.5**, lo que muestra cómo actúa la LGN también en distribuciones continuas.

---
## Ejemplo 3: Variable Bernoulli con $p = 0.3$

#### ¿Qué estamos haciendo?

Simulamos muchas repeticiones de un experimento que **tiene dos posibles resultados**:

- Éxito (1) con probabilidad $0.3$  
- Fracaso (0) con probabilidad $0.7$

Es como lanzar una moneda cargada donde solo 3 de cada 10 veces sale "cara".



####  ¿Cuál es el valor esperado?

La esperanza de una variable Bernoulli con parámetro $p$ es:
$$
\mathbb{E}[X] = p = 0.3
$$


#### ¿Qué vemos en el gráfico?

El **promedio acumulado** (es decir, la proporción de éxitos) **se estabiliza alrededor de 0.3** al aumentar las repeticiones.

La **Ley de los Grandes Números (LGN)** nos garantiza que, con suficientes ensayos, esa proporción se acercará cada vez más a la **probabilidad real del evento**.

---
##  Ejemplo 4: Variable Exponencial ($\lambda = 1$)

####  ¿Qué estamos haciendo?

Simulamos muchas veces un experimento aleatorio donde los valores siguen una **distribución exponencial**.  
Esta distribución modela **el tiempo que pasa entre eventos aleatorios**, por ejemplo, el tiempo entre llamadas en un centro de atención o el tiempo hasta que ocurre una falla.


####  ¿Cuál es el valor esperado?

Para una variable exponencial con parámetro $\lambda = 1$, el valor esperado (la media teórica) es:
$$
\mathbb{E}[X] = \frac{1}{\lambda} = 1
$$


####  ¿Qué vemos en el gráfico?

A medida que tomamos más muestras y calculamos el promedio, ese promedio se **acerca cada vez más al valor teórico de 1**.  
Esto ilustra la **Ley de los Grandes Números (LGN)**: el promedio de los resultados obtenidos se aproxima al valor esperado conforme aumenta el número de repeticiones.



---

##  ¿Por qué estos ejemplos ilustran la LGN?

Ambos ejemplos:

- Usan **variables aleatorias i.i.d.** (idénticamente distribuidas e independientes).
- Comparan el **promedio empírico** con el **valor esperado teórico**.
- Muestran cómo la diferencia entre ambos **disminuye al aumentar las muestras**.

 **Por tanto, ver el promedio estabilizarse visualmente es una manifestación clara de la Ley de los Grandes Números.**
