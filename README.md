# Spring_T1

Este es un proyecto basado en **Spring Boot**.

## Requisitos previos
Antes de ejecutar el proyecto, asegúrate de tener instalado lo siguiente:

- **Java JDK 17** o superior ([Descargar aquí](https://adoptium.net/))
- **Maven** ([Descargar aquí](https://maven.apache.org/download.cgi))
- **Git** ([Descargar aquí](https://git-scm.com/downloads))

## Instalación y ejecución

### 1. Clonar el repositorio
```bash
git clone https://github.com/Jaime-Gabriel-Hernandez-Garcia/Spring_T1.git
cd Spring_T1
```

### 3. Compilar y ejecutar
Ejecuta los siguientes comandos para compilar y ejecutar el proyecto:

```bash
mvn clean install
mvn spring-boot:run
```

El servidor debería iniciar en el puerto **8080** por defecto. Puedes acceder a la aplicación en:
```
http://localhost:8080
```

Si necesitas cambiar el puerto, edita el `application.properties`:
```properties
server.port=8081
```

## Pruebas
Para probar la API (si aplica), puedes usar **Postman** o **cURL**.

```bash
curl -X GET http://localhost:8080/api/ejemplo
```

## Autor
**Jaime Gabriel Hernández García**

## Grupo
**6CV4**
