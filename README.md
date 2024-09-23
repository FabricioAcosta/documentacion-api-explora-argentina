# Documentación de explora Argentina API REST


**Explora Argentina** es una API REST creada en Java que permite explorar diversas características y destinos turísticos de Argentina. Esta API está diseñada para ser consumida por aplicaciones frontend o cualquier servicio que requiera datos sobre destinos, actividades, y lugares turísticos en el país.

## Documentación de la API

La documentación completa de la API está disponible en Postman. Puedes acceder a la colección con todas las rutas y ejemplos de uso a través del siguiente enlace:

[**Explora Argentina - Documentación en Postman**](#) _(reemplaza este enlace con el verdadero)_

## Características de la API

- Registro de usuarios y autenticación.
- Gestión de destinos turísticos.
- Búsqueda por categorías y actividades.
- Funcionalidad de agregar y eliminar destinos.
- Listado de lugares recomendados.
- Información detallada sobre provincias y regiones.

## Requisitos previos

Antes de instalar y ejecutar la API, asegúrate de tener los siguientes requisitos cumplidos:

- **Java 17** o superior instalado.
- **Maven** instalado.
- **MySQL** (o la base de datos que prefieras) configurada y corriendo.
- **Postman** para probar las solicitudes.

## Instalación y Configuración

Sigue estos pasos para instalar y configurar la API en tu máquina local:

1. **Clona el repositorio**
   
``` bash
   git clone https://github.com/tu-usuario/explora-argentina.git
   cd explora-argentina
```
   
   **Configura la base de datos**

Crea una base de datos en MySQL (o el gestor de base de datos que prefieras):
```sql
CREATE DATABASE explora_argentina;
```
Actualiza las credenciales de la base de datos en el archivo `src/main/resources/application.properties`:
``` 
spring.datasource.url=jdbc:mysql://localhost:3306/explora_argentina
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
```


 **Compila y ejecuta la aplicación**

Compila y ejecuta la aplicación con Maven:
```bash
mvn clean install
mvn spring-boot:run
```
1.  La API estará disponible en `http://localhost:8080`.
    
2.  **Probar la API con Postman**
    
    Una vez que la API esté corriendo, puedes utilizar Postman para probar los distintos endpoints. Importa la colección de Postman desde el enlace proporcionado anteriormente y comienza a interactuar con la API.
    

## Contribuciones

Si deseas contribuir al proyecto, por favor sigue los pasos indicados en la [Guía de Contribución](CONTRIBUTING.md) y realiza un Pull Request.  


