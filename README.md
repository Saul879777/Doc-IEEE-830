# Doc-IEEE-830
Documento para la especificacion de requerimientos
Alumno
Registrar asistencia: En esta actividad una vez que el alumno  llega a la dependencia, registra la hora exacta en la que comienza sus actividades y termina de realizar actividades en la dependencia, ya sea mediante un checador, o algún otro método.
Consultar actividades: El alumno revisara las actividades que llevara a cabo dentro de la dependencia a lo largo de su servicio social y el documento que especifica las actividades lo firmara tanto la dependencia como el alumno.
Consultar reportes: El alumno podrá observar el progreso que lleva conforme los reportes que ha realizado a lo largo del servicio social, los cuales se realizan cada mes.
Consultar horas: El alumno podrá consultar las horas que ha reportado, para poder saber el progreso que lleva ante las 480 mínimas que se deben de reportar durante el servicio social.
Generar reporte de presentación en clase: El alumno generara su reporte de presentación en clase en el formato adecuado, con los datos requeridos para registrar su progreso.
Firmar formato de registro: La coordinación provee el formato de registro al alumno y será firmado por el alumno y el responsable de la dependencia.
Selección de opciones de SS: El alumno ingresara a la aplicación que provee la facultad para escoger 3 opciones de dependencias a las cuales prefiera.

Selección de opciones de SS: El alumno ingresara a la aplicación que provee la facultad para escoger 3 opciones de dependencias a las cuales prefiera.
Actor primario: Alumno
Alcance:
Nivel:
Precondiciones: 
1.- El alumno debe estar registrado en la aplicacion.
2- El alumno debe de haber cubierto el minimo de creditos para poder realizar el servicio social (75%).
Principal escenario de éxito:
1.- El alumno abrirá la aplicación que provee la facultad.
2.- Observara las opciones de SS.
3.- Elegirá las 3 que le parezcan mejor.
4.- el alumno guardara las opciones que elegió.
Extensiones:
1.- El alumno no selecciona ninguna opcion: la aplicacion mandara un mensaje de error en el cual dira que no ha elegido opciones.
2.-La opcion elegida no esta disponible: en este caso la aplicacion mandara un mensaje diciendo que la opcion no se encuentra disponible o esta llena.
Variaciones:

Registrar asistencia: En esta actividad una vez que el alumno  llega a la dependencia, registra la hora exacta en la que comienza sus actividades y termina de realizar actividades en la dependencia usando el sistema.
Actor primario: Alumno	.
Alcance: dependencia a la cual ira el alumno.
Nivel: meta de usuario.
Precondiciones: 
1.-El alumno debe estar registrado en el sistema.
2.- El alumno debe haber iniciado sesion en el sistema.
Principal escenario de éxito: 
1.  El alumno registra en el sistema la hora en la que comienza sus actividades seleccionando la opcion "registrar hora de entrada".
2.  El sistema registra la hora en que entro el alumno mediante un reloj interno.
3.  El sistema deja registrada la asistencia del alumno.
Extensiones:
1.- El usuario no pone la hora de inicio: en caso de que no registre la hora de entrada, el alumno no podra registrar la hora de salida y saldra un mensaje en el cual saldra un error.
2.- el usuario pone la hora de inicio pero no la de salida: en este caso cuando el alumno trate de salir del sistema, saldra un mensaje diciendo que no ha registrado la hora de salida y que si no lo hace se invalidara la hora de inicio.
Variaciones:

Requerimientos no funcionales
Restricciones
1-El sistema no sustituirá a la Academia, tampoco sustituirá el firmado de reportes y oficio ya que esto está declarado en el estatuto. Requerimiento organizacional, es por fuerza que la academia debe de participar en ciertos procesos del SS.
2.-Requerirá una conexión a Internet. Requerimiento del producto, no se ve a simple vista pero el sistema requiere de conexión a internet para poder  ser utilizado.
Suposiciones y dependencias
3.-El sistema será implementado de manera que sea multiplataforma. Requerimiento de portabilidad, esto se refiera a que pueda ser soportado en diferentes plataformas para la comodidad de quienes usan el sistema.
4.-No requerirá que los usuarios tengan una preparación especial para el uso del sistema. Requerimientos de usabilidad, el sistema debe de ser intuitivo lo que lo hará manejable y se identificaran los elementos que los componen, con iconos que sean familiares o entendibles a simple vista como ejemplo.
