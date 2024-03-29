# ProyectoFinalBackend
Instructivo para realizar las respectivas pruebas al proyecto integrador Backend

Requisitos Previos:

1. Asegúrate de tener instalado IntelliJ IDEA.
2. El proyecto está configurado para utilizar Java versión 17.
3. Los usuarios de prueba creados son los siguientes:

 
	1. Usuario Admin:

	Nombre: Mauricio
	Username: mau
	Email: mau@gmail.com
	Contraseña: 1234
	Rol: Administrador
	
	2. Usuario Común:

	Nombre: Cristina
	Username: cris
	Email: cris@gmail.com
	Contraseña: 1234
	Rol: Usuario Común

Pasos para Realizar Pruebas:

1. Desde IntelliJ IDEA, inicia el proyecto.

2. Una vez que el proyecto esté en ejecución, debería estar disponible en http://localhost:8080.

3. Inicia sesión utilizando el username y contraseña correspondientes para realizar las pruebas.

Para el usuario Admin, puedes usar:
Username: mau
Contraseña: 1234

Para el usuario Común, puedes usar:
Username: cris
Contraseña: 1234



Nota: El usuario Admin (ROL_ADMIN) tiene permisos para agregar, eliminar, modificar y listar Odontólogos, Pacientes y Turnos. 

El usuario Común (ROL_USER) tiene permisos únicamente para agregar, eliminar, modificar y listar Turnos. Si un usuario intenta realizar acciones no autorizadas, el servidor devolverá un estado 403 en la respuesta, lo que significa que la acción solicitada ha sido denegada.


6. Se realizaron las siguientes pruebas a este programa

Para la tabla Odontologos:
	1. Crear Odontologo
 	2. eliminar odontologo
	3. modificar odontologo
	4. listar odontologo

Para la tabla pacientes:
	1. Crear pacientes
 	2. eliminar pacientes
	3. modificar pacientes
	4. listar pacientes

Para la tabla turnos:
	1. Crear turnos
 	2. eliminar turnos
	3. modificar turnos
	4. listar turnos

Instrucciones Adicionales:

1. Una vez que hayas creado un Odontólogo, Turno o Paciente, podrás verlos en la lista correspondiente.

2. Para realizar una modificación en un registro, busca la opción "Modificar [nombre del registro]" en la parte inferior de la lista correspondiente. Selecciona el ID del registro que deseas modificar, el cual se encuentra en un botón azul.

3. Para eliminar un registro, simplemente haz clic en el botón rojo que dice "Eliminar" junto al registro.