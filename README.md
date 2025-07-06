# 📦 Proyecto Final: Sistema de Gestión de Productos y Pedidos

Repositorio oficial del proyecto **"Sistema de Gestión de Productos y Pedidos"** desarrollado como trabajo grupal para la asignatura **Programación III** (UTN).

---

## 🎯 Objetivo General
Crear una aplicación en **Laravel 12** que permita:
- Registrar productos (nombre, precio, stock, categoría).
- Crear pedidos con uno o más productos.
- Ver pedidos realizados.
- Controlar el stock automáticamente al realizar un pedido.

---

## 📝 Descripción del Proyecto
Este sistema está diseñado para pequeñas y medianas empresas que necesiten:
- Registrar y controlar su inventario de productos.
- Gestionar pedidos y ventas de manera sencilla.
- Llevar un historial de pedidos y ventas.
- Automatizar la gestión de stock.

La aplicación ofrece una **interfaz web amigable, responsive y 100% en español**, accesible desde cualquier dispositivo.

---

## 👥 Integrantes del Grupo:
| Nombre Completo               | Rol / Responsabilidad                            | Perfil de GitHub |
|-------------------------------|--------------------------------------------------|------------------|
| Romina Barrientos             | Desarrollo de CRUD y Vistas de Productos         | [GitHub](https://github.com/usuario1) |
| Valeria Avalos                | Desarrollo de API y Documentación Técnica        | [GitHub](https://github.com/usuario2) |
| Gustavo Ayala                 | Integración Backend y Relaciones de Base de Datos| [GitHub](https://github.com/usuario3) |
| Chavez Librada Noelia         | Diseño de Interfaces y Testing                   | [GitHub](https://github.com/usuario4) |
| Brandan Hugo                  | Autenticación, Livewire y Presentación Final     | [GitHub](https://github.com/brandanhugo) |


---

## 👥 Expectativas de los Usuarios
| Expectativa                               | Cómo lo resuelve el sistema                       |
|-------------------------------------------|--------------------------------------------------|
| Ver rápidamente los productos              | Página de productos con lista y acciones          |
| Controlar el stock actualizado             | Cada pedido descuenta automáticamente el stock    |
| Agregar productos fácilmente               | Formulario rápido de alta de productos            |
| Registrar pedidos                          | Formulario con selección de productos y cantidades|
| Consultar el historial de ventas           | Página con pedidos y sus detalles                 |
| No depender de Excel o papel               | Todo queda en la base de datos, ordenado          |

---

## 🛠️ Tecnologías Utilizadas:
- **Backend:** Laravel 12 (PHP)
- **Frontend:** Blade + Tailwind CSS + Livewire
- **Base de Datos:** MySQL o SQLite
- **API:** Endpoints internos para gestión de datos

---

## 🏗️ Etapas de Desarrollo:
1. **Planificación:** Definir funciones clave: productos, pedidos, stock.
2. **Diseño del Modelo:** Crear las tablas y relaciones necesarias.
3. **Desarrollo Backend:** Rutas, controladores, modelos y API.
4. **Desarrollo Frontend:** Vistas Blade con Tailwind CSS y Livewire.
5. **Pruebas:** Carga de productos, simulación de pedidos y control de stock.
6. **Mejoras:** Agregar autenticación, dashboard y reportes.

---

## 📂 Estructura del Proyecto:
```bash
📂 /app           # Modelos, controladores, Livewire, políticas, etc.
📂 /resources     # Vistas Blade, componentes Livewire y recursos CSS/JS
📂 /database      # Migraciones, factories y seeders
📂 /public        # Archivos públicos (imágenes, estilos compilados)
📂 /routes        # Archivos de rutas (web.php, api.php)
📂 /storage       # Archivos generados
README.md         # Documentación del proyecto (este archivo)
