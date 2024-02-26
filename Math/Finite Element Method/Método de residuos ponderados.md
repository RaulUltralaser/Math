util para aproximar una solución a una ecuación diferencial considere

$$ \frac{d^2u}{du}-u=-x,0<x<1$$
con $u(0)=u(1)=0$.
El primer paso es asumir una función de prueba con constantes desconocidas
$$\tilde{u}=ax(1-x)$$
> [!note]+ Nota
> 
La función satisface las condiciones iniciales

Una vez esta función es seleccionada, el residuo es calculado sustituyendo esta función en la ecuación diferencial 
$$R=\frac{d^2u}{du}-\tilde{u}+x=-2a-ax(1-x)+x$$

Una función ponderadora $w$ es seleccionada para ponderar el promedio del residuo sobre el dominio del problema y es igualado a cero, esto es:
$$I=\int_0^1wRdx=\int_0^1w(\frac{d^2u}{du}-\tilde{u}+x)dx=\int_0^1w\{-2a-ax(1-x)+x\}dx=0$$
El siguiente paso es decidir la función ponderadora. Algunos métodos son:

[[Método de colocación]]
[[Método de mínimos cuadrados]]
[[Método Garlekin]]

> [!note]+ Nota
> 
La aproximación resultante difiere dependiendo del método

Para mejorar la aproximación a esta solución, podemos añadir más términos a la función de prueba, por ejemplo:
$$a_1x(1-x)+a_2x^2(1-x)$$
[[Formulación débil]]