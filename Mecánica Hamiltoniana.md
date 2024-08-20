# Resumen
- Definición del Hamiltoniano
$$
H=K+U=\frac{p^{2}}{2m}+U
$$
- Ecuaciones de movimiento de Hamilton
$$
\begin{align}
\dot{x}&=\frac{ \partial H }{ \partial p }  \\
\dot{p}&=-\frac{ \partial H }{ \partial x }+F_{E} 
\end{align}
$$
- **Brackets de Poisson**
$$
\{F,G\}= \frac{ \partial F }{ \partial q_{i} }\frac{ \partial G }{ \partial p_{i} }- \frac{ \partial G }{ \partial q_{i} }\frac{ \partial F }{ \partial p_{i} } 
$$

# Brackets de Poisson
El bracket de Poisson es una operación que toma dos funciones de coordenadas generalizadas $F(q,p)$ y $G(q,p)$, y que se define de la siguiente forma:
$$
\{F,G\}= \frac{ \partial F }{ \partial q_{i} }\frac{ \partial G }{ \partial p_{i} }- \frac{ \partial G }{ \partial q_{i} }\frac{ \partial F }{ \partial p_{i} } 
$$
Esta definición tiene ciertas propiedades en función de la función que toma, por ejemplo:
- $\{ q,p \}$
$$
\begin{align}
\{ q,p \}&= \frac{ \partial q }{ \partial q }\frac{ \partial p }{ \partial p }-\frac{ \partial p }{ \partial x }\frac{ \partial x }{ \partial p }=1\cdot 1-0\cdot 0=1 \\
\{ q,p \}&=1
\end{align}
$$
- $\{ q,H \}$ donde $H= \frac{p^{2}}{2m}+U(x)$
$$
\begin{align}
\{ q,H \}&= \frac{ \partial q }{ \partial q }\frac{ \partial H }{ \partial p }-\frac{ \partial H }{ \partial q }\frac{ \partial q }{ \partial p }=1\cdot \frac{p}{m}-\left( \frac{dU}{dx}  \right)\cdot 0=\frac{\text{d}q}{\text{d}t} \\
\{ q,H \}&=\frac{\text{d}q}{\text{d}t} 
\end{align}
$$
- $\{ p,H \}$
$$
\begin{align}
\{ p,H \}&=\frac{ \partial p }{ \partial q } \frac{ \partial H }{ \partial p } -\frac{ \partial H }{ \partial q } \frac{ \partial p }{ \partial p }=0- \frac{\text{d}U}{\text{d}q} =\frac{\text{d}p}{\text{d}t} \\
\{ p,H \}&=\frac{\text{d}p}{\text{d}t}  
\end{align}
$$
Sea $Q(x(t),p(t))$
$$
\begin{align}
\frac{\text{d}Q}{\text{d}t}&=\frac{ \partial Q }{ \partial x } \frac{\text{d}x}{\text{d}t}+\frac{ \partial Q }{ \partial p }\frac{\text{d}p}{\text{d}t} \\
\frac{\text{d}x}{\text{d}t}&=\frac{ \partial H }{ \partial p } \\
\frac{\text{d}p}{\text{d}t}&=-\frac{ \partial H }{ \partial q }   \\
\frac{\text{d}Q}{\text{d}t}&=\frac{ \partial Q }{ \partial x }\frac{ \partial H }{ \partial p }-\frac{ \partial H }{ \partial x } \frac{ \partial Q }{ \partial p } \\
\frac{\text{d}Q}{\text{d}t}&=\{ Q,H \} 
\end{align}
$$
