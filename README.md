# sis_task
# Proyecto Laravel

Este es un proyecto backend construido con Laravel. Este proyecto incluye las rutas y controladores necesarios para gestionar las tareas.

## Instalación

1. Clonar el repositorio:
    ```bash
    git clone <repositorio-url>
    cd <nombre-del-directorio>
    ```
2. Instalar dependencias de Composer:
    ```bash
    composer install
    ```
3. Copiar el archivo `.env.example` a `.env` y configurar las variables de entorno:
    ```bash
    cp .env.example .env
    ```
4. Generar la clave de la aplicación:
    ```bash
    php artisan key:generate
    ```
5. Generar la clave de la aplicación:
    ```bash
    php artisan jwt:secret
    ```
6. Migrar la base de datos:
    ```bash
    php artisan migrate
    ```
7. Iniciar el servidor:
    ```bash
    php artisan serve
    ```

## Rutas y Endpoints
- **POST /api/login**: ingresar usuario.
- **POST /api/resgister**: Crear nuevo usuario.

- **GET /api/tasks**: Obtener todas las tareas.
- **GET /api/tasks/{id}**: Obtener una tarea específica por ID.
- **POST /api/tasks**: Crear una nueva tarea.
- **PUT /api/tasks/{id}**: Actualizar una tarea existente.
- **DELETE /api/tasks/{id}**: Eliminar una tarea.

## Dependencias

- **Laravel 10**: Framework PHP para construir la API.
- **JWT (JSON Web Token)**: Para la autenticación.

