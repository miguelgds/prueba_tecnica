# Proyecto amigo invisible
El cliente ACME SL ha contactado con nuestra empresa para ver si podemos ayudarlo en su nuevo proyecto. Han pensado en realizar internamente un amigo invisible para sus empleados. 
Para allá se ha desplazado nuestro analista funcional, y estas son las conclusiones a las que han llegado:

1) Permitir realizar el sorteo de emparejamientos de manera automatizada.
2) Tener en cuenta que algunos empleados tendrán restringido regalar a ciertos empleados.
3) El sorteo debe ser totalmente aleatorio.
4) Como resultado, se notificará a cada empleado a quien le ha tocado regalar.
5) En la notificación a cada empleado, se especificará que el importe del regalo no debe superar los 20€.  

NOTAS:
* El cliente nos ha proporcionado un fichero plano de donde se sacarán los participantes del sorteo (es el "participantes.txt" del raíz). El formato de cada una de las filas del mismo será: 
```
    <ID_EMPLEADO> # <NOMBRE_COMPLETO_EMPLEADO> [# <IDS_EMPLEADO SEPARADOS POR COMAS A LOS QUE NO PUEDE REGALAR>]. 
```

* En este primer entregable, el cliente quiere ver cómo funciona el programa y ha aceptado que el resultado del sorteo se notifiquen por consola. Nos ha pedido que tengamos en cuenta que para siguientes entregas querrá que se puedan tener distintos tipos de notificación (EMAIL, SMS, etc), por lo que nos pide que vayamos pensando en un diseño abierto a más tipos de notificación.

# Valores de nuestra empresa
Como todos nuestros empleados saben estos son, de mayor a menor importancia, nuestros valores como empresa:
1) **Desarrollamos modelos de dominio expresivos**: el código es entendible con sólo leerlo.
2) **Nos encanta el paradigma orientado a objetos bien aplicado**: nos basamos en la descomposición del problema en objetos autosuficientes que colaboran entre sí para realizar una tarea conjunta.
3) **Entregamos proyectos que cumplen los requisitos del cliente**: enfoque de mínimo producto viable.
4) **Entregamos un código testeado**: al menos tests unitarios de las partes más importantes.

# Requisitos de la prueba
1) Se ha establecido un tiempo máximo de 3 horas para su realización.
2) Se creará un branch con el nombre del candidato para realizar el desarrollo.
3) Se valorará positivamente el uso de spring-boot como framework para el desarrollo del proyecto.
4) Se valorará positivamente el uso de las capacidades de Java 8 cuando aplique (api de streams, expresiones lambda, etc).

