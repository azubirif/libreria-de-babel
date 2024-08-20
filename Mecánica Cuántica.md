# Conjugado de un valor complejo
El conjugado de un número complejo $z$ es expresa como $z^*$ tal que:
$$
|z|^{2}=z^*z
$$
Este conjugado consiste en multiplicar la parte compleja por $-1$:
- $z=a+bi\implies z^*=a-bi$
- $z=e^{i\theta}\implies z^*=e^{-i\theta}$
# Normalización de la ecuación de onda
Teniendo en cuenta que $|\psi (x,t)|^{2}$ representa la probabilidad de encontrar la partícula en una posición $x$, la probabilidad de que la partícula se encuentre en cualquier sitio debe ser $1$, o expresado matemáticamente:
$$
\int_{-\infty}^\infty |\psi (x,t)|^{2}\:\text{d}x=1
$$
Con esta ecuación podríamos encontrar la constante de la determinada ecuación de onda.
# Valor de expectativa
El valor de expectativa de una función $f(j)$ es:
$$
\langle j \rangle = \frac{\sum j N(j)}{N}=\sum_{j=0}^\infty j\:P(j)
$$
Siguiendo esta misma lógica aplicada a mecánica cuántica, donde $x$ es una posición, y la probabilidad de estar en esa posición es $|\psi (x,t)|^{2}$, entonces el valor de expectativa para la posición es:
$$
\langle  X\rangle_{\psi} = \int x |\psi (x,t)|^{2}dx
$$
