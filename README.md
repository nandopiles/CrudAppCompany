# README del Examen de 2º DAW - Ferran Piles Lablanca

¡Bienvenido al README más basado del examen de 2º DAW hecho por Ferran Piles Lablanca!

### Estructura de ficheros

```
└── 📁my-project
    └── .env
    └── .gitignore
    └── 📁bin
        └── console
    └── compose.override.yaml
    └── compose.yaml
    └── composer.json
    └── composer.lock
    └── 📁config
        └── bundles.php
        └── dbConfig.json
        └── 📁packages
            └── cache.yaml
            └── doctrine.yaml
            └── doctrine_migrations.yaml
            └── framework.yaml
            └── routing.yaml
            └── twig.yaml
        └── preload.php
        └── 📁routes
            └── framework.yaml
        └── routes.yaml
        └── services.yaml
    └── LICENSE
    └── 📁migrations
        └── .gitignore
    └── 📁public
        └── default.css
        └── 📁images
            └── img1.gif
            └── img2.jpg
        └── index.php
    └── 📁src
        └── 📁Controller
            └── .gitignore
            └── CrudController.php
            └── DetailController.php
            └── ListController.php
            └── MainController.php
        └── 📁Core
            └── 📁Interface
                └── IHeader.php
        └── 📁Entity
            └── .gitignore
            └── Client.php
            └── Emp.php
        └── Kernel.php
        └── 📁Repository
            └── .gitignore
            └── ClientRepository.php
            └── EmpRepository.php
    └── symfony.lock
    └── 📁templates
        └── base.html
        └── clientsList.html
        └── detail.html
        └── insert.html
        └── layout.html
        └── update.html
```


## Instrucciones para Corregir el Examen

Para corregir el examen, sigue estos simples pasos:

### 1. Clonar el Repositorio

Primero, necesitarás clonar este repositorio en tu máquina local. Puedes hacerlo ejecutando el siguiente comando en tu terminal:

```bash
git clone https://github.com/nandopiles/CrudAppCompany.git
```
### 2. Iniciar el Servicio de Docker

Después de haber clonado el repositorio, deberás iniciar el servicio de Docker. Abre la aplicación Docker Desktop y el servicio se iniciará automáticamente.

### 3. Levantar los Contenedores con Docker Compose

Sitúate en el directorio de trabajo donde clonaste el repositorio, asegurándote de estar al mismo nivel que el archivo docker-compose.yml. Luego, ejecuta el siguiente comando para levantar los contenedores:

```bash
docker-compose up
```

Este comando iniciará los 2 contenedores definidos en el arvhivo docker-compos.yml en los cuales está el docker de la aplicación y el docker de la base de datos MariaDb.

### 4. Verificar que los Contenedores Están en Ejecución

Para confirmar que los contenedores están en ejecución, utiliza el siguiente comando:

```bash
docker ps
```

Comprueba que los contenedores están marcados como "running".

### 5. Acceder al Archivo index.php

Después de asegurarte de que los contenedores están en ejecución, todo está listo para poder entrar a la aplicación así que, sitúate en cualquier navegador y accederemos a nuestro:

localhost:8000

¡Listo!
