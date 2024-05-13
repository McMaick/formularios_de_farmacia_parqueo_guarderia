# Proyecto de Farmacia

Este proyecto es una aplicación simple para gestionar el inventario de una farmacia. Incluye un formulario de registro para agregar medicamentos al inventario y una página de visualización de registros.

## Requisitos previos

- Servidor web (por ejemplo, Apache, Nginx)
- PHP
- MySQL o MariaDB

## Configuración

1. Clona el repositorio en tu máquina local:


2. Importa la base de datos:

   - Utiliza el archivo `base_de_datos.sql` proporcionado para importar la estructura de la base de datos en tu servidor MySQL o MariaDB.

3. Configura la conexión a la base de datos:

   - Abre el archivo `conexion.php` ubicado en la carpeta `controladores`.
   - Modifica las variables `$host_name`, `$database`, `$user_name` y `$password` con la información de tu servidor de base de datos.

## Uso

1. Abre la aplicación en tu navegador web e inicia sesión.
2. Completa el formulario de registro para agregar nuevos medicamentos al inventario.
3. Visualiza los registros de la farmacia en la página de visualización.

## Estructura del proyecto

- `index.php`: Página de inicio con el formulario de registro.
- `registros_farmacia.php`: Página para visualizar los registros de la farmacia.
- `controladores/conexion.php`: Archivo de conexión a la base de datos.
- `controladores/procesar_farmacia.php`: Controlador para el registro de la farmacia.
- `css/`: Carpeta que contiene los archivos CSS para el estilo de la aplicación.
- `js/`: Carpeta que contiene los archivos JavaScript (si es necesario).
- `img/`: Carpeta que contiene imágenes (si es necesario).
- `base_de_datos.sql`: Archivo SQL para importar la estructura de la base de datos.

## Contribución

Las contribuciones son bienvenidas. Si encuentras algún error o deseas mejorar la aplicación, no dudes en abrir un issue o enviar un pull request.

## Licencia

[MIT License](LICENSE)
