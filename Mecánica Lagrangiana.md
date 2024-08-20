La mecánica lagrangiana es una formulación de la mecánica clásica que se basa en el **principio de menor acción** o **principio de acción estacionaria**. Esta se basa en un **espacio configurativo** $M$ y en una función $L$ dentro de ese espacio conocida como el Lagrangiano.
# Principio de menor acción
Este principio establece que **una partícula en un determinado sistema seguirá aquella trayectoria que minimice el funcional de la acción**:
$$
\delta S = 0
$$
En concreto, la acción se define como:
$$
S=\int^{t_{2}}_{t_{1}} L\text\:{d}t
$$
Donde $L$ es el lagrangiano, definido como:
$$
L=T-V
$$
Donde $T$ es la energía cinética total del sistema y $V$ es la energía potencial total del sistema.
# Ecuación de Euler-Lagrange
Tras derivar del principio de menor acción, la ecuación que minimiza la acción para cada ecuación de movimiento es:
$$
\frac{ \partial L }{ \partial q }-\frac{\text{d}}{\text{d}t}\left( \frac{ \partial L }{ \partial \dot{q} }  \right)=0  
$$
Donde $q$ son las coordenadas generalizadas del sistema.
## Ejemplo - Masa atada a un muelle
Empezaremos definiendo:
- $T=\frac{1}{2}m \dot{x}^{2}$
- $V=\frac{1}{2}kx^{2}$
Por tanto, el lagrangiano del sistema es:
$$
L=T-V=\frac{1}{2}m \dot{x}^{2}-\frac{1}{2}kx^{2}=\frac{1}{2}(m \dot{x}^{2}-kx^{2})
$$
Si introducimos esta función en la ecuación de Euler-Lagrange:
$$
\begin{align}
\frac{ \partial L }{ \partial q }&=-kx \\
\frac{ \partial L }{ \partial \dot{q} }&=m\dot{x} \\
\frac{\text{d}}{\text{d}t}\frac{ \partial L }{ \partial \dot{q} }&=m\ddot{x}  \\
-kx-m\ddot{x}&=0 \\
m\ddot{x}&=-kx
\end{align}
$$
Para un sistema simple, la ecuación de Euler-Lagrange recrea el resultado que se hubiese obtenido con la segunda ley de Newton.