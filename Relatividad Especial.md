# Demostraciones
## $E=mc^{2}$
$$
\begin{align}
E&=\int F \text{d}r \\
&=\int\frac{\text{d}p}{\text{d}t} \text{d}r \\
&=\int \frac{\text{d}mv}{\text{d}t}\text{d}r \\
&=\int \left(   m\frac{\text{d}v}{\text{d}t} + \frac{\text{d}m}{\text{d}t}v \right) \text{d}r \\
\frac{\text{d}r}{\text{d}t}&=v\implies \\
&=\int mv\text{d}v+v^{2}\text{d}m
\end{align}
$$

# Espacio-tiempo
En relatividad especial, el espacio-tiempo es el continuo que forma el universo. Es un modelo que parte de tres dimensiones espaciales $(x,y,z)$ y una dimensión temporal $t$.
En tres dimensiones, el espacio está formado por **puntos** de tres coordenadas $x,y,z$.
En cuatro dimensiones, el espacio-tiempo está formado por **eventos**, que cuentan con una coordenada de tiempo $(x,y,z,t)$.
Si entre puntos en tres dimensiones hay una distancia, entre eventos hay un **intervalo de espacio-tiempo**.
# Intervalo de espacio-tiempo
En tres dimensiones, la distancia entre dos puntos se puede obtener mediante el teorema de Pitágoras:
$$
(\Delta d)^{2}= (\Delta x)^{2}+(\Delta y)^{2}+(\Delta z)^{2}
$$
Aunque las coordenadas específicas depende del **marco de referencia**, la distancia entre los puntos no cambia, independientemente del punto de vista.

Sin embargo, la distancia entre dos puntos entre dos puntos ni el tiempo en el que estos ocurren no es absoluto, pues en función de la velocidad relativa entre ambos observadores, el tiempo se dilata, las distancias se contraen, y los eventos no son simultáneos.

Por esto es necesario realizar correcciones a esta métrica de forma que su intervalo se independiente del observador.
$$
(\Delta d)^{2}=(c\Delta t)^{2} -(\Delta x)^{2}-(\Delta y)^{2}-(\Delta z)^{2}
$$
Esta corrección tiene en cuenta el tiempo entre ambos eventos. La constante $c$ se multiplica para tener todo en unidades de distancia.

Infinitesimalmente, esta métrica se convierte en:
$$
\text{d}s^{2}=-c^{2}\text{d}t^{2}+\text{d}x^{2}+\text{d}y^{2}+\text{d}z^{2}
$$
Es importante tener en cuenta el motivo del "extraño" cambio de signos en la métrica. Estas convenciones se conocen como "signaturas métricas", y consisten en colocar la coordenada del tiempo como la última.

En función de los valores de $s^{2}$, se pueden clasificar los diferentes intervalos:
- Si $s^{2}>0$, este intervalo se denomina **intervalo de tiempo**. Esto quiere decir que en este intervalo, un objeto masivo recorre **menos** distancia que la luz en el mismo intervalo de tiempo.
- Si $s^{2}<0$, se conoce como **intervalo de espacio**. Esto significa que un objeto masivo debería superar la velocidad de la luz para poder transmitir información al otro evento.
- Si $s^{2}=0$, significa que $x=\pm ct$. Esta clase de intervalos se conocen como **intervalos de luz**, en los que el objeto se mueve a velocidad $c$. Estos objetos (por ejemplo, fotones), no experimentan tiempo debido a la dilatación temporal:
$$
\lim_{ v \to c } t_{0}\sqrt{ 1-\frac{v^{2}}{c^{2}} }=0 
$$
## Cono de luz
![[diagram-20240806.png]]
Esto es un cono de luz o un diagrama de espacio-tiempo. Se utilizan para describir eventos y situaciones en cuatro dimensiones.
- La zona central donde cortan las rectas es el origen.
- La zona gris inferior es el pasado $(t<0)$. De igual forma, la superior es el futuro $(t>0)$.
- Las rectas amarillas son la luz propagándose por el espacio, y representan los intervalos de luz.
- Las zonas grises son las zonas donde uno puede comunicarse desde el origen, y representan los intervalos de tiempo $(v<c)$.
- Las zonas blancas son los intervalos de espacio, donde es imposible comunicarse $(v>c)$.
# Relatividad de la simultaneidad
En función de su velocidad relativa, dos o más observadores pueden no estar de acuerdos sobre en qué orden ocurrieron diferentes eventos. Un observador estático puede afirmar que una serie de eventos ocurrieron al mismo tiempo, mientras que otro en movimiento puede estar en desacuerdo.

Esto se debe a que