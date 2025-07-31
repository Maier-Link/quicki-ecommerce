# Quicki.com — E-commerce Platform 🛒

Quicki.com es una plataforma de comercio electrónico construida con **React**, **Node.js**, **Express** y **MongoDB**, diseñada para ofrecer una experiencia ágil de compra, administración de productos, manejo de usuarios y gestión de órdenes. El proyecto está centrado en escalabilidad, seguridad y facilidad de uso tanto para el cliente como para el administrador.

---

## ⚙️ Tecnologías utilizadas

- **Frontend:** React, Axios, React Router DOM
- **Backend:** Node.js, Express, MongoDB Atlas, Mongoose
- **Autenticación:** JWT, Bcrypt
- **Carga de imágenes:** Cloudinary
- **Panel Administrativo:** Visualización de métricas con Chart.js
- **Gestión de Entorno:** dotenv, CORS
- **Deployment:** V2Networks

---

## 🧩 Funcionalidades principales

- 📦 Catálogo de productos con filtros y búsqueda avanzada
- 🔒 Registro/login de usuarios y admins con validación de roles
- 🛒 Carrito de compras y órdenes con múltiples métodos de pago
- 🧑‍💼 Panel administrativo con CRUD completo de productos
- 📈 Estadísticas dinámicas (ventas, usuarios, productos)
- 🖼️ Carga y visualización de imágenes de productos vía Cloudinary
- 📧 Emails automáticos con Nodemailer (opcional)
- 📊 Exportación de reportes en CSV (opcional)

---

## 🚀 Instrucciones para ejecución local

```bash
# Clonar el repositorio
git clone https://github.com/Maier-Link/quicki-ecommerce.git

# Backend
cd backend
npm install
npm run dev

# Frontend
cd ../frontend
npm install
npm start
