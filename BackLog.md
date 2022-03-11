# LISTA DE ERRORES, BUGS, WARNINGS Y COSAS A SOLUCIONAR #

_________________________________________________________________

**ERROR**

Las hojas de estilos se muestran correctamente offline, pero
en un servidor local se rompe.
`Solución:`

**BUG**
El slider(Carrusel) de imagenes al momento de cambiar de imagen,
no es adaptable a el tamaño de las imagenes; lo que produce que
la pagina se mueva de arriba a abajo sola.
`Soluciones:`

1. Reajustar el comportamiento de el slider para que el tamaño
   sea estatico y centre la imagen ademas de ocultar el overflow.

2. Todas las imagenes que se suban al slider sean del mismo
   tamaño.

**WARNING**
Hay un problema de rendimiento en la carga de las imagenes del
slider, que es ocacionado por los multiples div que instancia
cada vez que pasa a la siguiente imagen.
`Solucion:`

1. Modificar el slider para que no haga una nueva instancia
   cada vez que va a pasar a la siguiente imagen, si no que
   cree una sola y esa misma sea modificada.

_________________________________________________________________

## MEJORAS ##

_Crear un script que suba las imagenes recientes_.
