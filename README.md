## 📓 INDICE DE CONTENIDO
### 🏗️  Laravel
* [Framework de Laravel](#about-laravel)
* [Documentación para aprender Laravel](#learning-laravel)
* [Sponsor de Laravel](#laravel-sponsors)
* [Patrocinadores de Laravel](#premium-partners)
* [Guía de contribución de Laravel](#contributing)
* [Vulnerabilidades de Seguridad de Laravel](#security-vulnerabilities)
* [Licencia Laravel](#license)
### 🚀 Proyecto
* [Acerca del proyecto](#acerca-del-proyecto)
* [Características](#️características)
* [Instalación](#️instalación)
* [Dependencias](#dependencias)

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## ACERCA DEL PROYECTO

Este proyecto es una muestra de una solución para administrar estudiantes y materias utilizando `PHP Laravel 8 + Bootstrap + MySQL`.

## CARACTERÍSTICAS

- [x] CRUD de usuarios
- [x] CRUD de estudiantes
- [x] Login

## INSTALACIÓN

Ejecutar aplicación.

```bash
dotnet run
```

### COMANDOS

```bash
# Crear proyecto
composer create-project laravel/laravel project-paradigmas

# Migración de base de datos
php artisan migrate

# Crear modelo de Estudiante (modelo-control-recurso)
php artisan make:model Estudiante -mcr

# Migración de tabla estudiante
php artisan migrate

#Ver rutas disponibles
php artisan route:list

#Abrir enlace para comunicarse con la carpeta de storage para imagenes
php artisan storage:link

#Agregar dependencias para autenticación
composer require laravel/ui

# Integrar bootstrap y autenticación
php artisan ui bootstrap --auth

# Procesar toda la aplicación
npm install

# Ejecutar build de integración
npm run dev
```

## Comandos utilizados para los Charts

```bash
# Crear controlador
php artisan make:controller ChartController

# Usar seeder para poblar la tabla de usuarios
php artisan db:seed
```
## RUN

Correr la aplicación.

```bash
 php artisan serve
 npm run dev
```
## DEPENDENCIAS

- [BarChart](https://cdnjs.com/libraries/Chart.js) Chart.JS Gráficos HTML5 simples usando el elemento canvas.

- [![npm version](https://badge.fury.io/js/alertifyjs.svg)](http://badge.fury.io/js/alertifyjs)

- [![jsDelivr Hits](https://data.jsdelivr.com/v1/package/npm/alertifyjs/badge?style=rounded)](https://www.jsdelivr.com/package/npm/alertifyjs)

### Install with [NPM](https://www.npmjs.com/package/alertifyjs/)

```
npm install alertifyjs --save
```