# Cash Card Application v1 - Spring Boot REST API

## Descripción

Este proyecto es una implementación de una API REST completa utilizando Spring Boot.
Durante el desarrollo de este proyecto, se exploran conceptos clave como la seguridad con Spring Security, persistencia de datos con Spring Data JDBC, y desarrollo de aplicaciones modernas con un enfoque en pruebas.

## Uso
La API permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre las tarjetas de débito digital. Algunas de las características principales incluyen:
- **Paginación y Filtrado:** Soporte para la recuperación de listas de tarjetas con capacidades de paginación y filtrado.
- **Manejo de Errores:** Asegurando que no se revelen datos sensibles.
## Tecnologías Utilizadas

- **Spring Boot**: Framework para crear aplicaciones Java de manera rápida y sencilla.
- **Spring Security:** Framework que provee seguridad a nivel de autenticación y autorización.
- **Spring Data JDBC:** Facilita la conversión automática entre objetos Java y la base de datos
- **H2 Database**: Base de datos en memoria utilizada para el almacenamiento persistente de datos durante el desarrollo.
- **Spring Web**: Para manejar las comunicaciones HTTP.
- **Gradle:** Herramienta de construcción que maneja dependencias y automatizan tareas

## Prerrequisitos
Antes de comenzar, asegúrate de tener instaladas las siguientes herramientas:
- Java 17+
- Gradle 7+
- Un IDE como IntelliJ IDEA o Eclipse

## Pruebas
El proyecto incluye una suite de pruebas automatizadas que cubren tanto la funcionalidad principal de la API como los aspectos de seguridad.
### Tipos de pruebas implementadas:
- Pruebas de Integración: Verifican la correcta integración de los componentes de la aplicación, incluyendo controladores, servicios y repositorios.
- Pruebas de Seguridad: Aseguran que solo los usuarios autenticados y autorizados puedan acceder a los recursos protegidos.
- Pruebas de Persistencia: Validan que los datos se almacenen y recuperen correctamente utilizando Spring Data JDBC.

## Instalación

Para configurar y ejecutar el proyecto localmente, sigue estos pasos:

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/pzric/CashCard-v1.git
   
2. **Navegar al directorio del proyecto**:
   ```bash
      cd CashCard-v1

3. **Navegar al directorio del proyecto**:
   ```bash
      ./gradlew build

4. **Ejecutar la aplicación**:
   ```bash
      ./gradlew bootRun
   
## Ejecución de las pruebas:
Para ejecutar las pruebas, utiliza el siguiente comando:
   ```console
   ./gradlew test
   ```

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.

## Author ✒️

* **Ricardo Zamora Picazo** - [Ricardo ZP](https://github.com/pzric)
* **Spring Academy** - [Spring Academy](https://spring.academy/)


## Reconocimientos   
Agradecimientos a la comunidad de Spring y a los recursos educativos que ayudaron a hacer posible este proyecto.

