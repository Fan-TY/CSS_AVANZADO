Las animaciones web en CSS son una forma de aplicar movimiento y transiciones a los elementos de una página web de manera fluida y
controlada, sin necesidad de JavaScript.
Estas animaciones se definen usando la regla @keyframes para describir los diferentes estados de la animación y luego se aplican a un elemento con la
propiedad animation.


keyframes:
• Es la regla que define los estilos de la animación

_______________________________________________________________________________________

animation: Es la propiedad abreviada que permite controlar cómo se aplica la animacióna
un elemento. Combina varias sub-propiedades, como:
• animation-name: El nombre de la regla @keyframes que se va a usar.
• animation-duration: La duración de un ciclo completo de la animación.
• animation-timing-function: La curva de velocidad de la animación (por ejemplo, linear,
ease-in, ease-out).
• animation-iteration-count: Cuántas veces se repetirá la animación

_______________________________________________________________________________________
La animation-delay propiedad especifica un retraso para el inicio de una animación




_______________________________________________________________________________________
La propiedad especifica si una animación debe reproducirse hacia adelante, hacia atrás o
en ciclos alternativos. animation-direction
La propiedad animation-direction puede tener los siguientes valores:
• normal: La animación se reproduce normalmente (hacia adelante). Esta es la
configuración predeterminada.
• reverse: La animación se reproduce en dirección inversa (hacia atrás)
• alternate: La animación se reproduce primero hacia adelante y luego hacia atrás.
• alternate-reverse: La animación se reproduce primero hacia atrás y luego hacia
adelante