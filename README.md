# Tienda de Mascotas Lilool 🐾

Este repositorio contiene el desarrollo completo de la tienda en línea **Lilool**, un sitio web orientado a la venta de productos para mascotas y la difusión de contenido educativo relacionado con el cuidado animal.

Lilool nace con el propósito de ofrecer un espacio virtual accesible, organizado y amigable para los amantes de los animales, permitiendo explorar una gran variedad de productos, conocer más sobre el bienestar de las mascotas y establecer una comunicación directa con la tienda.

👉 **Visita la tienda en línea aquí:**  
🔗 [https://carito0323.github.io/TiendaLilool/](https://carito0323.github.io/TiendaLilool/)

Este sitio web ofrece una experiencia completa de compra y aprendizaje para los amantes de los animales, integrando un catálogo interactivo, blog educativo, opiniones de clientes, contacto directo por redes sociales y la posibilidad de crear cuentas para compras personalizadas.

> ⚠️ Nota: Debido a que parte del contenido del sitio (productos, opiniones, redes sociales, etc.) se carga dinámicamente desde la base de datos SQL, dichos datos no se visualizarán al acceder directamente al enlace del sitio, a menos que se esté trabajando en un entorno local con conexión activa a la base de datos.

---

## 🔧 Tecnologías Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **Base de Datos SQL**

---

## 🗂 Estructura del Sitio Web

La página web de **Lilool** está dividida en varias secciones funcionales y visuales para mejorar la experiencia del usuario:

### 🏠 Página Principal

La página de inicio brinda una introducción visual e informativa de la tienda e incluye:

- 🐶 **Logo de Lilool** y breve descripción de la tienda
- 🖼 **Carruseles de imágenes**:
  - Productos destacados
  - Fotografías de clientes con sus mascotas
- 📚 **Categorías organizadas** por:
  - Tipo de animal (perros, gatos, aves, roedores, etc.)
  - Tipo de producto (alimentos, juguetes, accesorios, higiene, salud, entre otros)
- 🔗 **Enlaces a redes sociales** para contacto directo y seguimiento

---

### 🛍 Página de Productos

Sección donde se muestra todo el catálogo de productos disponibles, cargado dinámicamente desde la base de datos. Cada producto incluye:

- 📸 Imagen del producto
- 🏷 Nombre
- 💲 Precio
- 📝 Descripción detallada

Los productos están organizados por categoría, facilitando la navegación y búsqueda para el usuario.

---

### 📲 Página de Redes Sociales

Una página dedicada a las diferentes plataformas de contacto de **Lilool**, incluyendo:

- Facebook
- Instagram
- WhatsApp
- Correo electrónico

Se presenta con íconos interactivos y enlaces directos para facilitar la comunicación entre clientes y la tienda.

---

### 🐕‍🦺 Página de Blog

Contiene artículos informativos y curiosos relacionados con el mundo animal. Algunos de los temas abordados incluyen:

- Cuidados básicos de diferentes especies
- Alimentación según edad y raza
- Datos curiosos y comportamiento animal
- Recomendaciones sobre productos

El contenido busca educar, entretener y fortalecer el vínculo entre humanos y mascotas.

---

### ⭐ Página de Opiniones

Sección donde los clientes pueden dejar sus valoraciones y comentarios sobre sus compras, atención recibida o experiencias con los productos de **Lilool**. Estas opiniones se almacenan en la base de datos y se cargan dinámicamente.

Incluye:

- Nombre del cliente
- Calificación (estrellas)
- Comentario
- Fecha de publicación

---

### 👤 Sistema de Cuentas y Compras

El sitio incluye una funcionalidad para que los usuarios puedan:

- Crear una cuenta personal
- Iniciar sesión
- Explorar productos con su cuenta activa
- Realizar compras (carrito de compras funcional condicionado a iniciar sesión para usarlo)

> Esta funcionalidad está conectada directamente con la base de datos SQL, por lo que para pruebas completas es necesario ejecutarlo en un entorno local con acceso a la base de datos.

---

## 📁 Estructura del Repositorio

- 📁 `TiendaLilool`: Carpeta principal que contiene el código fuente HTML, CSS y JavaScript del sitio.
- 🗃️ `db_lilool`: Base de datos SQL utilizada para almacenar productos, usuarios, opiniones y redes sociales.

---

## 🧩 Funcionalidades Destacadas

- Interfaz amigable y adaptable a dispositivos móviles
- Integración con base de datos para gestión dinámica del contenido
- Navegación clara por categorías
- Sistema de registro y autenticación de usuarios
- Blog educativo y opiniones en tiempo real
- Contacto directo con la tienda mediante redes sociales

---

## ⚠ Limitaciones

- Debido a la integración con la base de datos, varios elementos del sitio **no se mostrarán correctamente** en la vista pública del sitio si no hay conexión con la base de datos local.
- Para una visualización completa, se recomienda clonar el repositorio y ejecutarlo en un entorno de desarrollo local con conexión a la base de datos SQL correspondiente.

---

## 🚀 Créditos

Este proyecto fue desarrollado con dedicación y esfuerzo, como parte de un un proyecto universitario.

---

## 📄 Licencia

No está autorizado el uso ni distribución sin previo consentimiento.

---

**Lilool – Todo lo que tu mascota necesita, en un solo lugar.**  
🐾💚
