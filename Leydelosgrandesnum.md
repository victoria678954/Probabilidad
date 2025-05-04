# Ley de los Grandes Números (LGN)

## Ley Débil de los Grandes Números (LGN débil)

Sea $X_1, X_2, \dots$ una sucesión de variables aleatorias i.i.d. (independientes e idénticamente distribuidas) con esperanza $\mu = \mathbb{E}[X_i]$ y varianza finita $\sigma^2$.

Definimos el promedio muestral como:

$$
\bar{X}_n = \frac{1}{n} \sum_{i=1}^n X_i
$$

Entonces, la ley débil dice que:

$$
\bar{X}_n \xrightarrow{P} \mu \quad \text{cuando } n \to \infty
$$

Es decir, el promedio converge en **probabilidad** al valor esperado $\mu$.

---

## Ley Fuerte de los Grandes Números (LGN fuerte)

Bajo las mismas condiciones, la forma fuerte establece que:

$$
\bar{X}_n \xrightarrow{\text{c.s.}} \mu \quad \text{cuando } n \to \infty
$$

Es decir, el promedio converge **casi seguramente** (con probabilidad 1) al valor esperado. Esta es una forma más fuerte de convergencia.

---

## Símbolos

- $\bar{X}_n$: Promedio de las primeras $n$ variables aleatorias.
- $\bar{X}_n = \frac{1}{n} \sum_{i=1}^n X_i$: Fórmula explícita del promedio.
- $\xrightarrow{P}$: Convergencia en probabilidad.
- $\xrightarrow{\text{c.s.}}$: Convergencia casi segura (con probabilidad 1).
- $\mu$: Esperanza matemática o valor esperado.
- $n \to \infty$: El número de observaciones tiende a infinito.

---

## NOTA:

Ambas formas de la Ley de los Grandes Números dicen que, si repetimos un experimento muchas veces y calculamos el promedio de los resultados, ese promedio se acercará al valor esperado teórico.

- **LGN débil:** El promedio se acerca *probablemente* al valor esperado.
- **LGN fuerte:** El promedio se acerca *con certeza* (salvo en casos de probabilidad cero).
