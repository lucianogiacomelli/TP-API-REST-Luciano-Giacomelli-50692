# TP API REST

Este es un proyecto de ejemplo realizado con JPA, Envers, y una base de datos en memoria H2. El proyecto está diseñado para demostrar el uso de entidades, relaciones y auditoría en un contexto de API REST.

## Tecnologías Utilizadas

- **Java**: Lenguaje de programación.
- **JPA (Java Persistence API)**: Para la persistencia de datos.
- **Hibernate Envers**: Para la auditoría de cambios en las entidades.
- **H2 Database**: Base de datos en memoria para pruebas.

## Configuración del Proyecto


## Estructura del Proyecto
- **audit**: Contiene la clase Revision.
- **config**: Contiene la clase CustomRevisionListener para la auditoría.
- **controllers**: Contiene el controlador de Persona, Autor y Localidad.
- **entities**: Contiene las entidades Autor, Base, Domicilio, Libro, Localidad, Persona.
- **repositories**: Contiene el repositorio de Persona, Autor y Localidad.
- **services**: Contiene la interfaz AutorService, PersonaService y LocalidadService, con sus Implementaciones.

## Ejecutar el Proyecto
### Paso 1
Descargar el repositorio de GitHub.

```bash
git clone https://github.com/XxFabio24xX/TPApiRest
```
### Paso 2
Abrir el proyecto en IntelliJ IDEA.
### Paso 3
Ejecutar el archivo 'Inicial1Application.java' dentro del proyecto.

### Paso 4
- En el navegador: 
  - Abrir la consola de H2: ("localhost:8080/h2-console")\
  [H2 Console](http://localhost:8080/h2-console)
  - Abrir la consola de OPEN API: ("localhost:8080/swagger-ui/index.html")\
  [OPEN API](http://localhost:8080/swagger-ui/index.html)



## Autor


## Luciano Giacomelli 50692
## 3K10