# Laravel Veterinario usando Filament.php

Un back office es la parte interna de una empresa donde se gestionan tareas administrativas, financieras y operativas que no están directamente relacionadas con el contacto con el cliente.

Con Laravel v-12 y package Filament.php, el package Filament.php facilita crear paneles de administración rápidos y personalizables en aplicaciones Laravel. Permite a los desarrolladores crear interfaces de usuario intuitivas para gestionar datos, usuarios y flujos de trabajo dentro de un back office, sin necesidad de escribir código HTML o CSS complejo.

## Instalación

1. Clonar repositorio.
   `git clone https://github.com/cdelcastillomaussa/veterinario.git`

2. Instalar paquetes de composer.
   `composer install`

3. Crear archivo .env.
   `cp .env.example .env`

4. Crear llave.
   `php artisan key:generate`

5. Configurar la base de datos en el archivo .env
   `Decidi usar mysql`

6. Ejecuta las migraciones.
   `php artisan migrate`

## Ejecutar proyecto

1. Ejecutar la aplicacion
   `php artisan serve`
2. Crear user dentro de Filament.php
   `php artisan make:filament-user`
3. Digirirse a su navegador e ir a la siguiente URL
   `127.0.0.1:8000/admin`

## Convención para los mensajes de commits

En Git, los mensajes de commit siguen ciertas convenciones para describir el propósito del cambio. Estas convenciones son especialmente útiles en proyectos grandes o colaborativos, ya que ayudan a mantener un historial de cambios claro y coherente. Aquí te explico qué significa cada uno de los tipos de commit que mencionas y cuándo usarlos, con ejemplos:

1. **feat**: Una nueva característica para el usuario.

    - **Cuándo usarlo**: Cuando implementas una nueva funcionalidad o característica en el código.
    - **Ejemplo**:
        - `feat: add user login functionality`
        - `feat: implement dark mode toggle`

2. **fix**: Solución a un bug.

    - **Cuándo usarlo**: Cuando corriges un error o bug en el código.
    - **Ejemplo**:
        - `fix: resolve issue with incorrect user permissions`
        - `fix: fix null pointer exception in data processing`

Estos tipos de commits ayudan a mantener un historial claro y permiten a los colaboradores entender rápidamente qué tipo de cambio se realizó sin tener que revisar el código detalladamente.
