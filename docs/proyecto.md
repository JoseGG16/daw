# 📗 Documentación del Proyecto Intermodular – VerdeGo

## 🟢 1. Introducción
**VerdeGo** es una tienda online de frutas, verduras y productos naturales cuyo objetivo es ofrecer al usuario una experiencia de compra rápida, clara y sostenible.  
El proyecto incluye tanto la parte pública (tienda online) como un **panel de administración** para gestionar empleados, productos, pedidos y clientes.

La aplicación está desarrollada utilizando **HTML, CSS, JavaScript** y puede integrarse con tecnologías Java como **JSP, Servlets y DAOs** para el backend.

---

## 🟢 2. Objetivos del Proyecto
- Ofrecer una tienda online funcional con un diseño moderno y accesible.  
- Implementar un sistema de carrito, pedidos y fidelización por puntos.  
- Permitir a los clientes gestionar su perfil, pedidos y datos personales.  
- Incluir un sistema de roles para permitir administración interna de la tienda.  
- Dotar al administrador de herramientas para gestionar productos, pedidos, usuarios y empleados.

---

## 🟢 3. Tecnologías utilizadas

### ✔ Frontend
- HTML5  
- CSS3  
- JavaScript  
- Diseño responsive  
- Uso de modales, toasts y drawer lateral

### ✔ Backend (según implementación)
- JSP (Java Server Pages)  
- Servlets  
- DAOs  
- MySQL / MariaDB  
- Patrón MVC

### ✔ Herramientas
- Figma / Figma Make  
- Git / GitHub  
- Navegadores web modernos

---

## 🟢 4. Estructura general de la aplicación

### 4.1 Parte pública (cliente)
- **Pantalla de inicio**  
  - Hero principal  
  - Buscador  
  - Productos destacados  

- **Pantalla de productos**  
  - Listado completo  
  - Filtrado por categorías  
  - Buscador  

- **Carrito de compra (drawer lateral)**  
  - Cantidades dinámicas  
  - Subtotal, envío e IVA  
  - Aplicación de código de descuento  
  - Canje de puntos  

- **Pedidos del cliente**  
  - Histórico  
  - Estado del pedido  
  - Detalle

- **Perfil del usuario**  
  - Datos personales  
  - Dirección  
  - Método de pago (PayPal)  
  - Puntos acumulados

---

### 4.2 Panel de Administración
- **Panel principal** con acceso a:  
  - Gestión de productos  
  - Gestión de pedidos  
  - Gestión de clientes  
  - Gestión de empleados  
  - Ajustes generales  

#### Gestión de empleados
- Listado completo  
- Crear empleado (pantalla propia)  
- Editar empleado (pantalla propia)  
- Eliminar empleado (confirmación)

#### Gestión de productos
- Listado  
- Crear producto  
- Editar producto  
- Eliminar producto

#### Gestión de pedidos
- Tabla con pedidos  
- Despliegue de detalle por pedido  

#### Gestión de clientes
- Listado de clientes  
- Posibilidad de eliminar cuentas

---

## 🟢 5. Sistema de Fidelización
Los clientes obtienen puntos por cada compra:

- **100 puntos por cada 10 € gastados**.  
- Al alcanzar **1000 puntos**, pueden canjearlos por **5 € de descuento**.  

Los puntos se muestran en su perfil y en la pantalla de checkout.

---

## 🟢 6. Interacciones y Ventanas Superpuestas

### ✔ Toasts (éxito)
- Empleado creado  
- Cambios guardados  
- Producto añadido  
- Producto eliminado  

### ✔ Modales de Confirmación
- Finalizar compra  
- Eliminar producto  
- Eliminar empleado  
- Confirmar creación del empleado  
- Confirmar guardado de cambios  

### ✔ Modal de Error
- Fallo al guardar  
- Fallo al procesar compra  

### ✔ Modal de Compra Finalizada
Incluye número de pedido, icono ✔ y botones de navegación.

---

## 🟢 7. Principios de comunicación visual
El diseño se apoya en los principios de alineación, contraste, jerarquía, proximidad y equilibrio para garantizar una experiencia clara y accesible.  
La alineación mantiene orden; el contraste resalta información relevante; la jerarquía guía la navegación visual; la proximidad agrupa contenido relacionado; y el equilibrio distribuye el peso visual de forma armoniosa.

---

## 🟢 8. Paleta de colores y tipografía

### 🎨 Paleta principal
- Verde 900: `#0b4d2d`  
- Verde 700: `#167a4b`  
- Verde 100: `#e6f4ec`  

### 🎨 Colores de apoyo
- Amarillo advertencia: `#F5C542`  
- Rojo error: `#D9534F`  
- Fondo gris claro: `#f6f9f7`  

### ✏ Tipografía
- **Arial** (legible, accesible y universal)

La elección garantiza claridad, accesibilidad y coherencia con una estética natural y profesional.

---

## 🟢 9. Arquitectura del Sistema (si se usa Java + JSP)
- `/views` → JSPs  
- `/controllers` → Servlets  
- `/models` → Clases Java (Producto, Pedido, Usuario, Empleado…)  
- `/dao` → Acceso a datos  
- `/assets` → CSS, JS, imágenes  
- `/WEB-INF` → Configuración interna  

---

## 🟢 10. Conclusión
VerdeGo es una aplicación completa y moderna que integra una tienda online funcional, un sistema de fidelización, un panel administrativo y una interfaz limpia basada en principios profesionales de diseño.  
El proyecto demuestra competencias en diseño UI, desarrollo web y organización de sistemas completos.

---
