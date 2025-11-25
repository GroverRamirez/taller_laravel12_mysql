<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/95/Vue.js_Logo_2.svg" width="120" alt="Vue Logo" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Laravel.svg/985px-Laravel.svg.png" width="120" alt="Laravel Logo" />
</p>

<h1 align="center">Taller: Sistema Web con Laravel 12 y MySQL</h1>

En esta guía encontrarás las **herramientas y tecnologías** necesarias para el taller de 4 a 5 horas donde desarrollaremos un sistema web básico con **PHP Laravel 12**, **MySQL** y **phpMyAdmin**, usando vistas con **Blade** y estilos con **Bootstrap o Tailwind**.

---

## 1. Programas obligatorios para el taller

Estos sí o sí deben estar instalados antes de la clase 👇

- [Visual Studio Code](https://code.visualstudio.com/)  
  Editor de código principal para trabajar el proyecto Laravel.

- [PHP 8.x](https://www.php.net/downloads.php)  
  Versión compatible con Laravel 12.

- [Composer](https://getcomposer.org/download/)  
  Gestor de dependencias para instalar y actualizar Laravel.

- **Servidor local (uno de los dos):**
  - [XAMPP](https://www.apachefriends.org/es/index.html)  
    Incluye Apache, PHP y MySQL + phpMyAdmin.
  - [Laragon](https://laragon.org/)  
    Alternativa ligera para Windows con Apache/Nginx + MySQL.

- **MySQL / MariaDB**  
  Ya viene dentro de XAMPP/Laragon, será nuestro motor de base de datos relacional.

- **phpMyAdmin**  
  Panel web para:
  - Crear la base de datos del sistema.
  - Ver tablas, datos y relaciones.
  - Probar consultas SQL.

- [Node.js (LTS)](https://nodejs.org/es/)  
  Necesario para Vite (build de assets de Laravel) aunque en el taller usaremos Blade con CSS simple o Bootstrap.

---

## 2. Herramientas recomendadas (no obligatorias, pero ayudan)

Estas no son críticas para el taller, pero sirven para la materia completa DPWIII:

- [Git](https://git-scm.com/)  
  Control de versiones (guardar historial del proyecto).

- [Docker Desktop](https://www.docker.com/get-started)  
  Para entornos más avanzados (no se usará en el taller rápido).

- [TablePlus](https://tableplus.com/)  
  Cliente gráfico de bases de datos (alternativa a phpMyAdmin).

- [Postman](https://www.postman.com/)  
  Útil para pruebas de APIs cuando veamos backend tipo API REST.

---

## 3. Extensiones de VSCode recomendadas

### Para HTML, PHP, Laravel y Vue

- [Laravel](https://marketplace.visualstudio.com/items?itemName=laravel.vscode-laravel)  
  Snippets y ayudas para trabajar con Laravel.

- [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)  
  Autocompletado y análisis para PHP.

- [Vue Language Features (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.volar)  
  Para cuando trabajemos con Vue 3 en la parte SPA de la materia.

- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)  
  Autocompletado de clases si usamos Tailwind en el frontend.

### Utilidades generales

- [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)  
  Para reorganizar la barra lateral de VSCode.

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)  
  Cierra etiquetas HTML automáticamente.

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)  
  Cambia la etiqueta de cierre cuando editas la de apertura.

- [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)  
  Convierte JSON a interfaces/clases (útil cuando trabajemos APIs).

- [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)  
  Para proyectos Vue/TS más adelante.

- [Better Dockerfile Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-dockerfile-syntax)  
  Solo si usas Docker en entornos más avanzados (no en el taller corto).

---

## 4. Extensiones de Chrome

- [JSON Viewer Awesome](https://chrome.google.com/webstore/detail/json-viewer-pro/eifflpmocdbdmepbjaopkkhbfmdgijcc)  
  Muestra las respuestas JSON de forma ordenada cuando probemos APIs.

---

## 5. Tema y personalización (opcional)

No es obligatorio, pero mejora la experiencia de trabajo en VSCode:

- [Aura Dark Theme](https://marketplace.visualstudio.com/items?itemName=DaltonMenezes.aura-theme)  
  Tema oscuro recomendado.

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)  
  Iconos para carpetas y archivos (Laravel, PHP, Vue, etc.).

---

> ✅ Resumen rápido para el taller de 4–5 horas:  
> **Obligatorio:** VSCode, PHP 8, Composer, XAMPP/Laragon (MySQL + phpMyAdmin), Node.js, navegador.  
> **Opcional:** Git, Docker, TablePlus, Postman, temas e iconos.

