# [Elaborado por Fabián Suárez](https://www.linkedin.com/in/inge-fabiansuarez/)

## Página Web Personal

Este proyecto es una página web personal diseñada para presentar un portafolio profesional y facilitar la actualización automática de la información desde LinkedIn, además de mostrar repositorios de GitHub en un formato de tarjeta atractivo con íconos de redes sociales. La página permite a los visitantes explorar fácilmente tus logros, proyectos, y contribuciones técnicas.

La integración con LinkedIn automatiza la sincronización de cambios en tu perfil profesional, manteniendo tu página web actualizada en tiempo real. Esta funcionalidad es especialmente útil para profesionales del área de desarrollo de software, pues permite una gestión centralizada del perfil profesional, sin necesidad de realizar actualizaciones manuales.

Adicionalmente, la página utiliza Firebase Firestore para gestionar la autenticación y persistir la información de login del usuario, proporcionando una experiencia segura y personalizada.

## Manual de Implementación o Instalación



  

1. Unzip the downloaded archive

2. Copy and paste **soft-ui-dashboard-laravel-master** folder in your **projects** folder. Rename the folder to your project's name

3. In your terminal run `composer install`

4. Copy `.env.example` to `.env` and updated the configurations (mainly the database configuration)

5. In your terminal run `php artisan key:generate`

6. Run `php artisan migrate --seed` to create the database tables and seed the roles and users tables

7. Run `php artisan storage:link` to create the storage symlink (if you are using **Vagrant** with **Homestead** for development, remember to ssh into your virtual machine and run the command from there).

  


## Navegadores Soportados


  

<img  src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png"  width="64"  height="64">  <img  src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png"  width="64"  height="64">  <img  src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png"  width="64"  height="64">  <img  src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png"  width="64"  height="64">  <img  src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png"  width="64"  height="64">

  
## Creditos

  

- [Fabián Enrique Suárez Carvajal](https://www.linkedin.com/in/fabian-enrique-suarez-carvajal)
