# 🖥️ Simpsons Store Front

**Front-end del proyecto Simpsons Store Back** para administrar y comprar muñecos de Los Simpsons.

Este repositorio contiene la interfaz visual desarrollada en **HTML, CSS y JavaScript** que se conecta al backend del proyecto [`simpsonsstore-back`](https://github.com/carreon81/simpsonsstore-back).

---

## 🚀 Descripción

Permite a los usuarios:

- Ver productos disponibles con imágenes, precio, stock y descripción.
- Agregar productos al carrito.
- Visualizar el carrito con total acumulado.
- Realizar pedidos seleccionando productos del carrito.
- Ver y administrar pedidos realizados.
- Panel de administración para agregar, editar y gestionar productos.

---

## 🛠️ Tecnologías

- HTML5
- CSS3
- JavaScript
- Bootstrap 5 (opcional según la estructura)
- Fetch API para consumir endpoints REST del backend

---

## 📦 Instalación y ejecución

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/carreon81/simpsonsstore-front.git
cd simpsonsstore-front

Ejecutar la aplicación
No requiere compilación ni dependencias, basta con abrir index.html en tu navegador:

Puedes utilizar Live Server en VS Code para mayor comodidad.
Asegúrate de que el backend simpsonsstore-back esté corriendo en:
http://localhost:8081

⚙️ Configuración

Si deseas apuntar a otro puerto o URL del backend, ajusta en tus archivos JavaScript las URL utilizadas en los fetch, por ejemplo:

const apiUrl = "http://localhost:8081";
🗂️ Estructura de archivos

index.html - Página principal con listado de productos.
detalle.html - Vista de detalle de producto.
carrito.html - Carrito de compras.
admin.html - Administración de productos.
pedidos.html - Visualización y gestión de pedidos.
header.html - Encabezado reutilizable incluido en otras vistas.
✅ Requisitos para funcionar

Tener corriendo el backend de simpsonsstore-back.
La base de datos simpsonsdb con datos cargados desde el backend.
Conexión a internet para cargar imágenes externas


👨‍💻 Autor

Desarrollado por Emmanuel Carreón.

📄 Licencia

Este proyecto es de uso educativo y libre de utilizar para prácticas de Spring Boot + Front HTML.

