git
> [!definition] Base de una topología
> Sea $(X,\tau)$ un espacio topológico. Una colección $\beta$  de subconjuntos abiertos de $X$ se dice que es una base para la topología $\tau$ si todo conjunto abierto es una unión de miembros de $\beta$.

Ejemplo:

Sea $\beta=\{(a,b):a,b\in\mathbb{R},a<b\}$. Entonces $\beta$ es una base para la topología euclidiana en $\mathbb{R}$, por la proposición dos en [[Euclidian topology]]

Ejemplo:

Sea $X=\{a,b,c,d,e,f\}$ y $\tau=\{X,\emptyset,\{a\},\{c,d\},\{a,c,d\},\{b,c,d,e,f\}\}$
Entonces $\beta=\{\{a\},\{c,d\},\{b,c,d,e,f\}\}$ es una base para $\tau$ ya que $\beta\subseteq\tau$ y todo miembro de $\tau$ puede ser expresado como una unión de miembros de $\beta$ (Nótese que $\emptyset$ es una unión vacía de miembros de $\beta$)