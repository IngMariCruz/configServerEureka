# configServerEureka

Este proyecto implementa un **Config Server** que centraliza las configuraciones de todos los microservicios en la arquitectura. El Config Server proporciona configuraciones centralizadas para los microservicios, como Eureka, Usuario, Curso, entre otros. Los microservicios pueden consumir estas configuraciones de manera dinámica sin necesidad de tener archivos de configuración locales.

## Componentes del Proyecto

- **Archivos de Configuración**: Cada microservicio tendrá su propia configuración en formato `application.properties`, que se cargará desde el Config Server.
- **Guía para crear el config server**
- **Rutas Locales y API Gateway**: El archivo `urlsEureka.txt` contiene información sobre las rutas locales de los microservicios y las rutas que deben ser usadas a través del API Gateway.

## Requisitos

- Java 11 o superior
- Maven 3.8.x o superior

## Configuración del Config Server

1. **Iniciar el Config Server**: 
   - Asegúrate de que el Config Server esté corriendo para que todos los microservicios puedan obtener su configuración centralizada.
   - El Config Server debe estar vinculado a un repositorio Git o a un sistema de archivos donde estén almacenadas las configuraciones de los microservicios.

2. **Configurar para ejecitar el proyecto**:
   - ConfigServer
   - Eureka
   - Usuario
   - Curso
   - Gateway

