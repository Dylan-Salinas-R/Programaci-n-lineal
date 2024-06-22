Antes de usar esta herramienta debe tener en cuenta lo siguiente:

1. La explicación de este documento es solamente de aspectos de utilización de la herramienta, da por sentado de que usted tiene conocimientos acerca de
la programación lineal, sus aplicaciones y conocimiento del software Excel. 
2. Su diseño es exclusivo para realizar programación lineal.
3. La plantilla ya se encuentra automatizada, sin embargo usted debera realizar el procedimiento de usar el complemento de
solver de Excel para resolver el sistema, esta plantilla unicamente le ayudara a digitar mas facil las restricciones y variables
del sistema.

Consideraciones especificas

1. Unicamente debe modificar las celdas que se encuentran de color palo rosa claro.
2. Las celdas que tiene como encabezado "condicion" poseen una lista desplegable que le permitira seleccionar el tipo de restriccion que se debe cumplir (aplica unicamente
para la programación lineal simple y el metodo de transporte, para el metodo de asignación esto no es necesario)
3. La celda con el encabezado "Objetivo Z" es el valor objetivo que debe poner en solver.
4. Las celdas de color amarillo son las celdas cambiantes que debe ingresar en solver.
5. Debe seleccionar para resolver el sistema en solver "simplex LP"
6. La herramienta se divide en 3 plantillas para un sistema en especifico los cuales son los siguientes:

Plantilla 1: Programación lineal simple (posee una capacidad maxima de trabajar con 20 restricciones y 10 variables)
Plantilla 2: Programación lineal metodo de transporte (Posee una capacidad maxima de trabajar con 10 restricciones y 10 variables)
Plantilla 3: Programación lineal metodo de asignación (Posee una capacidad maxima de trabajar con 10 restricciones y 10 variables)

7. Para los sitemas de metodo de transporte (plantilla 2) cuentan con un sistema de formato condicional que le permitira saber si se esta consumiendo por completo
lo requerido y lo disponible, para ello simplemente debe realizar una interpolación entre filas y columnas, para asi descubrir donde se esta consumiendo por completo o
si existe holgura entre algun valor de las celdas cambiantes, donde cada color indica la siguiente (Aplica para filas y columnas)

Color rojo: Existe holgura
Color verde: No existe holgura
Sin color: No hay valores en la filas o columnas 

Nota: El formato condicional se observara en la columna "Disponible" y la fila "Requerido" que se encuentra en la matriz de celdas cambiantes. Esto se analiza una vez
resuelto el sistema.

8. Para los sistemas de metodo de asignación (Plantilla 3) tambien cuenta con un sistema de formato condicional, donde se mostrara el formato condicional en la ultima columna
de la derecha y la ultima fila inferior en la matriz que tiene las celdas cambiantes; igualmente para identidicar si existe holgura o no debera realizar una interpolación entre
las filas y columnas, aunque en este metodo no existe holgura; donde el formato significa lo siguiente:

Color rojo: Existe holgura
Color verde: No existe holgura
Sin color: No hay valores en la filas o columnas 

Nota: Recuerde esto se analiza una vez resuelto el sistema.

SI TIENE ALGUN PROBLEMA CON LA HERRAMIENTA O ALGUNA DUDA SOBRE SU UTILIZACIÓN, LIMITACIONES O DETECTO UN ERROR EN EL DISEÑO, NO DUDE EN CONTACTARME PARA PODER ACLARAR SUS DUDAS.

Atentamente.

DYLAN MARCELO SALINAS RAMOS
