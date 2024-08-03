# Family Cash Card Application

## Descripción

La aplicación Family Cash Card es una solución moderna para que los padres administren las asignaciones de sus hijos. En lugar de manejar dinero en efectivo, los padres pueden utilizar esta aplicación para enviar, recibir y rastrear fondos mediante tarjetas de efectivo virtuales, similares a las tarjetas de regalo.

## Objetivos del Proyecto

Este proyecto tiene los siguientes objetivos principales:

- **Construir una API RESTful completa**: Utilizando Spring Boot, crear una API que permita realizar operaciones CRUD sobre las tarjetas de efectivo.
- **Aplicar buenas prácticas de desarrollo**: Implementar validaciones de reglas de negocio, autenticación y autorización, y asegurar la API contra accesos no autorizados y exploits.
- **Fomentar una arquitectura bien estructurada**: Utilizar una arquitectura en capas para separar las responsabilidades y facilitar el mantenimiento del código.
- **Adoptar un enfoque de desarrollo basado en pruebas**: Escribir pruebas antes de la implementación para asegurar que la aplicación funcione según lo diseñado.

## Funcionalidades

La aplicación Family Cash Card permite realizar las siguientes operaciones:

- Crear una nueva tarjeta de efectivo
- Obtener todas las tarjetas de efectivo
- Obtener una tarjeta de efectivo específica
- Actualizar una tarjeta de efectivo
- Eliminar una tarjeta de efectivo

## Tecnologías Utilizadas

- **Spring Boot**: Framework principal para la construcción de la API.
- **Spring Web**: Para manejar las comunicaciones HTTP.
- **Spring Security**: Para implementar autenticación y autorización.
- **H2 Database**: Base de datos en memoria utilizada para el almacenamiento persistente de datos durante el desarrollo.

## Prerrequisitos

Antes de comenzar, asegúrate de tener instaladas las siguientes herramientas:

- Java 17+
- Gradle 7+
- Un IDE como IntelliJ IDEA o Eclipse

## Instalación

Sigue estos pasos para configurar y ejecutar el proyecto:

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/pzric/CashCard.git
   cd CashCard
   
1. **Compila y ejecuta el proyecto:**:

   ```bash
   ./gradlew bootRun

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.

## Author ✒️

* **Ricardo Zamora Picazo** - [Ricardo ZP](https://github.com/pzric)
* **Spring Academy** - [Spring Academy](https://spring.academy/)


