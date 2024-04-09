# Gestión de Reserva de Citas Odontológicas

_Este proyecto desarrollado en Java utilizando Spring Boot, Maven y H2 como base de datos, tiene como objetivo facilitar la gestión de reservas de citas entre profesionales odontológicos y pacientes. Implementa el patrón DAO para una eficiente persistencia de datos._

## Características principales 👓

1. Persistencia de datos: Utiliza H2 como base de datos para almacenar la información de usuarios, citas y profesionales.
2. Patrón DAO: Se ha implementado el patrón DAO para separar la lógica de acceso a datos de la lógica de negocio, facilitando así el mantenimiento y escalabilidad del sistema.
3. Operaciones CRUD: La aplicación permite realizar operaciones de creación, lectura, actualización y eliminación de usuarios, citas y profesionales.

## Tecnologías utilizadas ⚙️

Este proyecto se desarrolló utilizando las siguientes tecnologías:

Java 17
maven:3.9.6
Spring Boot

### Instrucciones de Clonación 🔧

_Si deseas clonar el repositorio y explorar el código en un entorno de desarrollo, sigue estos pasos:_


1. Clona el repositorio desde GitHub:
```
git clone <URL_del_repositorio>
```
2. Navega hasta el directorio del proyecto:
```
cd nombre_del_proyecto
```
3. Asegúrate de tener instalado Java 17 en tu sistema.

4. Compila el proyecto utilizando Maven:
```
mvn clean install
```
5. Una vez compilado, ejecuta el servidor Spring Boot:
```
mvn spring-boot:run

```

Una vez que el servidor esté en funcionamiento, podrás acceder a la API localmente desde cualquier cliente HTTP.

También tienes la opción de clonar el repositorio desde GitHub y trabajar con él en IntelliJ IDEA como tu entorno de desarrollo preferido. Para hacerlo, sigue estos pasos:

1. Clona el repositorio desde GitHub como se explicó anteriormente.

2. Abre IntelliJ IDEA.

3. Selecciona "File" en la barra de menú y luego "Open" para abrir el proyecto clonado desde el directorio en el que lo has guardado.

4. Una vez que el proyecto se haya cargado en IntelliJ, asegúrate de tener configurado el JDK correspondiente (Java 17 en este caso) en la configuración del proyecto.

5. Puedes ejecutar el código directamente desde el IDE. Simplemente busca la clase principal o el punto de entrada de la aplicación y haz clic con el botón derecho en ella. Luego selecciona "Run" para iniciar la aplicación.

Esta opción te permite trabajar con el código de una manera más cómoda y familiar si estás acostumbrado a utilizar IntelliJ IDEA como tu entorno de desarrollo integrado.

## Información para correr la app ▶️

1. Los usuarios de prueba creados son los siguientes:

Usuario Admin:
Nombre: Mauricio Username: mau Email: mau@gmail.com Contraseña: 1234 Rol: Administrador

Usuario Común:
Nombre: Cristina Username: cris Email: cris@gmail.com Contraseña: 1234 Rol: Usuario Común

_Nota: El usuario Admin (ROL_ADMIN) tiene permisos para agregar, eliminar, modificar y listar Odontólogos, Pacientes y Turnos._

El usuario Común (ROL_USER) tiene permisos únicamente para agregar, eliminar, modificar y listar Turnos. Si un usuario intenta realizar acciones no autorizadas, el servidor devolverá un estado 403 en la respuesta, lo que significa que la acción solicitada ha sido denegada.

2. Instrucciones Adicionales:

Una vez que hayas creado un Odontólogo, Turno o Paciente, podrás verlos en la lista correspondiente.

Para realizar una modificación en un registro, busca la opción "Modificar [nombre del registro]" en la parte inferior de la lista correspondiente. Selecciona el ID del registro que deseas modificar, el cual se encuentra en un botón azul.

Para eliminar un registro, simplemente haz clic en el botón rojo que dice "Eliminar" junto al registro.
## Ejecutando las pruebas ⚙️

Durante el desarrollo de este proyecto, todas las pruebas fueron realizadas de forma manual, empleando un conjunto de técnicas y herramientas de pruebas ampliamente reconocidas. Estas pruebas incluyeron pruebas de regresión y pruebas de humo, entre otras.

Se realizaron las siguientes pruebas a este programa

1. Para la tabla Odontologos: 1. Crear Odontologo 2. eliminar odontologo 3. modificar odontologo 4. listar odontologo

2. Para la tabla pacientes: 1. Crear pacientes 2. eliminar pacientes 3. modificar pacientes 4. listar pacientes

2. Para la tabla turnos: 1. Crear turnos 2. eliminar turnos 3. modificar turnos 4. listar turnos

## Construido con 🛠️

* ([Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)) - Versión del lenguaje de programación Java utilizada.
* ([Maven](https://maven.apache.org/)) - Herramienta de gestión de proyectos utilizada para construir y gestionar dependencias.
* ([Spring Boot](https://spring.io/projects/spring-boot)) - Framework utilizado para crear aplicaciones Java de manera rápida y sencilla.

## Autores ✒️

* **Maurin Cristina Arturo** - *Backend Dev* - [MCristina94](https://github.com/MCristina94)

---
⌨️ con ❤️ por [MCristina94](https://github.com/MCristina94)😊