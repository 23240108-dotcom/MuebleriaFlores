# Flores Mobiliario — Sistema Web de Cotizaciones y Administración

## Descripción

Flores Mobiliario es una plataforma web enfocada en la administración y cotización de muebles para oficinas, recepciones y espacios comerciales.

El sistema permite a los clientes:

* Registrarse e iniciar sesión
* Explorar el catálogo de muebles
* Agregar productos a una cotización
* Consultar el historial de solicitudes
* Administrar su perfil

También incluye un panel administrativo para:

* Gestionar productos
* Administrar inventario
* Revisar cotizaciones
* Aceptar o rechazar solicitudes
* Generar reportes
* Respaldar información mediante JSON

Todo el sistema utiliza `LocalStorage` como almacenamiento local del navegador.

---

# Tecnologías utilizadas

* HTML5
* CSS3
* JavaScript Vanilla
* LocalStorage

---

# Funcionalidades principales

## Clientes

### RF1 — Registro de usuarios

Los usuarios pueden crear una cuenta proporcionando:

* Nombre
* Apellidos
* Correo electrónico
* Teléfono
* Contraseña

---

### RF2 — Inicio de sesión

Los clientes pueden autenticarse para acceder a sus funciones personalizadas.

---

### RF3 — Consulta de catálogo

Los usuarios pueden:

* Ver productos
* Buscar muebles
* Filtrar por categorías
* Ordenar por precio y stock

---

### RF4 — Generación de cotizaciones

Los clientes pueden:

* Agregar productos
* Modificar cantidades
* Eliminar productos
* Ver subtotales y total general

---

### RF5 — Historial de cotizaciones

Cada usuario puede consultar sus solicitudes anteriores y el estado de cada una.

---

### RF6 — Gestión de perfil

El usuario puede:

* Actualizar sus datos
* Cambiar contraseña
* Eliminar su cuenta

---

### RF7 — Persistencia local

Toda la información se guarda mediante `LocalStorage`.

---

# Funcionalidades administrativas

## RF8 — Registro de administradores

Se pueden crear administradores mediante una clave de autorización.

Clave:
DUENA-FLORES

---

## RF9 — Inicio de sesión administrativo

Los administradores tienen acceso al panel de control.

---

## RF10 — Gestión de productos

El administrador puede:

* Crear productos
* Editar productos
* Eliminar productos
* Modificar stock

---

## RF11 — Gestión de cotizaciones

El administrador puede:

* Revisar solicitudes
* Aceptar cotizaciones
* Rechazar cotizaciones
* Editar cantidades

---

## RF12 — Gestión de administradores

Los administradores pueden actualizar su información.

---

## RF13 — Reportes

El sistema genera indicadores como:

* Total de ventas aceptadas
* Total de cotizaciones
* Inventario disponible
* Productos registrados

---

## RF14 — Respaldo de información

El sistema permite:

* Exportar respaldo JSON
* Importar respaldo JSON

---

# Cuenta administrativa inicial

Correo:
[admin@flores.com](mailto:admin@flores.com)

Contraseña:
admin123

---

# Estructura del proyecto

```text
FloresMobiliario/
│
├── index.html
├── productos.html
├── cotizacion.html
├── perfil.html
├── login.html
├── registro.html
├── registro-admin.html
├── admin.html
├── reportes.html
├── contacto.html
│
├── css/
│   └── estilos.css
│
├── js/
│   └── app.js
│
├── banner.jpg
├── logo.png
├── silla.jpg
├── escritorio.jpg
├── recepcion.jpeg
└── ...
```

---

# Compatibilidad

Compatible con:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox

---

# Recomendación

Este proyecto utiliza LocalStorage para almacenamiento local.

Para un entorno profesional o de producción se recomienda utilizar:

* Backend
* Base de datos real
* Sistema de autenticación segura
* API REST

---

# Autor

Proyecto desarrollado para la gestión y cotización de mobiliario profesional.
