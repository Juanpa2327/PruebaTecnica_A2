#  Proyecto Laravel API & Angular Frontend

Este proyecto está dividido en **dos partes principales**:  
1. **Backend (API REST)** desarrollado en **Laravel**  
2. **Frontend  desarrollado en **Angular**

---

## Estructura del proyecto

```
 proyecto/
 ┣  backend/        # API REST desarrollada en Laravel
 ┣  frontend/       # Aplicación Angular (vistas e interacción)
 ┣ base_datos.sql  # Exportación de la base de datos
 ┣  postman.json    # Colección de peticiones para Postman
```

---

##  Instalación y configuración

###  **Requisitos previos**

- [Node.js](https://nodejs.org/en/) (con `npm`)
- [Composer](https://getcomposer.org/)
- [PHP 8+](https://www.php.net/)
- [Angular CLI](https://angular.io/cli)
- [MySQL](https://www.mysql.com/)

---

 Ejecuta las migraciones (opcionalmente también puedes importar el archivo SQL):
   ```bash
   php artisan migrate
   ```

 Inicia el servidor:
   ```bash
   php artisan serve
   ```



Inicia el servidor de desarrollo:
   ```bash
   ng serve
   ```

El frontend quedará disponible normalmente en  
 **http://localhost:4200**

---

##  Postman

En la raíz del proyecto encontrarás una **colección de Postman (`postman.json`)**  
que contiene las peticiones para probar el **API REST** de Laravel.


---

##  Base de Datos

El repositorio incluye el archivo **`base_datos.sql`** con la exportación completa.  
Puedes importarlo directamente en MySQL



---

##  Desarrollado por

Proyecto desarrollado con **Laravel** + **Angular** como práctica de integración **FullStack**.  
Incluye API REST, migraciones, vistas dinámicas, y pruebas con Postman.
