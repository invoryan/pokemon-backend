# Proyecto Laravel: Pokemon-Backend

Este proyecto es una aplicación web que gestiona los datos de los Pokémon. Está desarrollado en **Laravel 12** utilizando una **arquitectura hexagonal** y **Domain-Driven Design (DDD)**. Proporciona una API y una interfaz para consultar, agregar y gestionar información sobre Pokémon.

---

## **Requisitos del sistema**

- PHP 8.2 o superior.
- Composer (para gestionar dependencias).
- Node.js y npm (para compilar assets).
- MySQL (como base de datos).
- Git (para control de versiones).

---

## **Instalación**

Sigue estos pasos para configurar el proyecto en tu entorno local:

1. **Clona el repositorio:**:

   ```bash
   git clone https://github.com/invoryan/pokemon-backend.git
   cd nombre-del-repositorio
   ```
2. **Instala las dependencias de Composer:**:

   ```bash
   composer install
   ```
3. **Instala las dependencias de Node.js:**:

   ```bash
   npm install
   ```
4. **Configura el archivo .env:**:

   ```bash
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=pokemon
    DB_USERNAME=root
    DB_PASSWORD=
   ```
5. **Ejecuta las migraciones y los seeders:**:

   ```bash
   php artisan migrate:fresh --seed
   ```
6. **Inicia el servidor:**:

   ```bash
   php artisan serve
   ```
---
# Estructura del proyecto

El proyecto sigue una arquitectura hexagonal y Domain-Driven Design (DDD), lo que significa que está organizado en módulos según el dominio de la aplicación (en este caso, Pokémon). Aquí hay una descripción general de la estructura:
- app/Domain: Contiene la lógica de negocio y las entidades del dominio.
- app/Application: Contiene los casos de uso y la lógica de aplicación.
- app/Infrastructure: Implementaciones de interfaces externas (por ejemplo, repositorios, servicios externos).
- app/Http/Controllers: Controladores que manejan las solicitudes HTTP.
---
# Autor
- Bryan Hurtado 

---
