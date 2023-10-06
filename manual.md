# Manual de Estilo y Prácticas - Trianametria Project

## Introducción
Este manual de estilo y prácticas tiene como objetivo proporcionar pautas y recomendaciones para el desarrollo de aplicaciones en Trianametria Project. Estas pautas ayudarán a mantener un código limpio, coherente y fácil de mantener.

## Convenciones de Nomenclatura
Trianametria Project sigue las siguientes convenciones de nomenclatura:

- **Clases y Objetos:** Nombres de clases y objetos en camelCase (por ejemplo, `miClase`).
- **Métodos:** Nombres de métodos en camelCase (por ejemplo, `miMetodo()`).
- **Variables:** Nombres de variables en camelCase (por ejemplo, `miVariable`).
- **Constantes:** Nombres de constantes en mayúsculas con guiones bajos (por ejemplo, `MI_CONSTANTE`).

## Estructura de Carpetas y Archivos
La estructura de carpetas y archivos en una aplicación desarrollada con el Proyecto XYZ debe seguir la siguiente estructura:

- /root
- /assets
- /auth
- /endpoints
- /firewall
- /core
- /config
- /views
    - /index.php
- /frontend
    - /scripts
    - /styles
- /vendor

## Archivos de Configuración
Las configuraciones de la aplicación deben mantenerse en archivos dentro de la carpeta `/config` y se deben cargar de manera centralizada en la aplicación.

## Controladores
- Los controladores deben estar en la carpeta `/core`.

## Vistas
- Las vistas deben estar en la carpeta `/views` y utilizar un motor de plantillas si es necesario.
- Se recomienda separar las vistas de la lógica tanto como sea posible, direccionamos los estilos a `/frontend/styles` y los scripts a `/frontend/scripts`. 

## Servicios
- La arquitectura esta basada en servicios, los cuales son integrados en la base de datos para una correcta autenticación y autorización, dichos servicios se guardan en la ruta `/endpoints`
