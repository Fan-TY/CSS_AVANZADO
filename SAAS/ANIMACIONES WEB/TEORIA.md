Las transiciones CSS le permiten cambiar los valores de las propiedades sin problemas, durante una duración determinada.

transition es una propiedad CSS abreviada para:
• transition-property (Requerido)
• transition-duration (Requerido)
• transition-timing-function
• transition-dela

IMPORTANTE: La transición se activa cuando se produce un cambio en las propiedades del elemento. Esto suele ocurrir dentro de pseudoclases (:hover, :active, :focus o :checked).

____________________________________________________________________________

transition-timing-function
La propiedad especifica la curva de velocidad del efecto de transición

• ease- la transición comenzará lenta, luego irá rápida y finalizará lenta (esto es predeterminado)
• linear- La transición mantendrá la misma velocidad de principio a fin.
• ease-in- La transición comenzará lentamente
• ease-out- La transición terminará lentamente
• ease-in-out- La transición tendrá un comienzo y un final lentos.
• cubic-bezier(n,n,n,n)- le permite definir sus propios valores en una función cúbica-bezier

__________________________________________________________________________

Retraso de transición CSS
El transition-delay especifica un retraso antes de que comience la transición.

