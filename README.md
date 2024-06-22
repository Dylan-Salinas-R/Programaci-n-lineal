Antes de usar esta herramienta, debe tener en cuenta lo siguiente:

La explicación de este documento se enfoca únicamente en aspectos de utilización de la herramienta. Da por sentado que usted tiene conocimientos acerca de la programación lineal, sus aplicaciones y el software Excel.
Su diseño es exclusivo para realizar programación lineal.
La plantilla ya se encuentra automatizada; sin embargo, usted deberá realizar el procedimiento de usar el complemento Solver de Excel para resolver el sistema. Esta plantilla únicamente le ayudará a digitar más fácilmente las restricciones y variables del sistema.
Consideraciones específicas:

Únicamente debe modificar las celdas que se encuentran de color palo rosa claro.

Las celdas que tienen como encabezado "Condición" poseen una lista desplegable que le permitirá seleccionar el tipo de restricción que se debe cumplir (aplica únicamente para la programación lineal simple y el método de transporte; para el método de asignación esto no es necesario).

La celda con el encabezado "Objetivo Z" es el valor objetivo que debe poner en Solver.

Las celdas de color amarillo son las celdas cambiantes que debe ingresar en Solver.

Debe seleccionar para resolver el sistema en Solver "Simplex LP".

La herramienta se divide en 3 plantillas para un sistema en específico, las cuales son las siguientes:

Plantilla 1: Programación lineal simple (posee una capacidad máxima de trabajar con 20 restricciones y 10 variables).
Plantilla 2: Programación lineal método de transporte (posee una capacidad máxima de trabajar con 10 restricciones y 10 variables).
Plantilla 3: Programación lineal método de asignación (posee una capacidad máxima de trabajar con 10 restricciones y 10 variables).
Para los sistemas del método de transporte (Plantilla 2), se cuenta con un sistema de formato condicional que le permitirá saber si se está consumiendo por completo lo requerido y lo disponible. Para ello, simplemente debe realizar una interpolación entre filas y columnas para así descubrir dónde se está consumiendo por completo o si existe holgura entre algún valor de las celdas cambiantes. Cada color indica lo siguiente (aplica para filas y columnas):

Color rojo: Existe holgura.
Color verde: No existe holgura.
Sin color: No hay valores en las filas o columnas.
Nota: El formato condicional se observará en la columna "Disponible" y la fila "Requerido" que se encuentra en la matriz de celdas cambiantes. Esto se analiza una vez resuelto el sistema.

Para los sistemas del método de asignación (Plantilla 3), también se cuenta con un sistema de formato condicional, donde se mostrará el formato condicional en la última columna de la derecha y la última fila inferior en la matriz que tiene las celdas cambiantes. Igualmente, para identificar si existe holgura o no, deberá realizar una interpolación entre las filas y columnas. Aunque en este método no existe holgura, el formato significa lo siguiente:

Color rojo: Existe holgura.
Color verde: No existe holgura.
Sin color: No hay valores en las filas o columnas.
Nota: Recuerde, esto se analiza una vez resuelto el sistema.

SI TIENE ALGÚN PROBLEMA CON LA HERRAMIENTA O ALGUNA DUDA SOBRE SU UTILIZACIÓN, LIMITACIONES O DETECTÓ UN ERROR EN EL DISEÑO, NO DUDE EN CONTACTARME PARA PODER ACLARAR SUS DUDAS.

Atentamente,

DYLAN MARCELO SALINAS RAMOS
