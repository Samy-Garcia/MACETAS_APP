<img width="3780" height="1890" alt="Green Illustration Minimalist Community Gathering Banner (1)" src="https://github.com/user-attachments/assets/8d3ae46a-81c8-41ed-ac48-7ee2fea3d2f1" />

# 🌱 MACETAS 503

Sistema web para la administración y contratación de servicios relacionados con macetas y jardinería.

El proyecto está desarrollado con una arquitectura **Frontend + Backend**, utilizando **React**, **Node.js**, **Express** y **MongoDB**.

---

#  Características

- Inicio de sesión.
- Registro de usuarios.
- Recuperación de contraseña mediante código de verificación.
- Administración de perfiles.
- CRUD de usuarios.
- CRUD de clientes.
- CRUD de servicios.
- CRUD de reseñas.
- CRUD de categorías.
- Búsqueda de información.
- Panel administrativo.
- Rutas protegidas.
- Validaciones en cliente y servidor.
- Notificaciones mediante Toast.
- Diseño Responsive.

---

# Tecnologías utilizadas

## Frontend

- React
- React Router DOM
- React Hook Form
- Framer Motion
- Lucide React
- React Hot Toast
- React Phone Number Input
- SweetAlert2
- Tailwind CSS
- Shadcn UI

## Backend

- Node.js
- Express
- MongoDB
- Mongoose
- JWT (JSON Web Token)
- BcryptJS
- Cookie Parser
- Cors
- Dotenv
- Nodemailer
- Multer
- Cloudinary
- Multer Storage Cloudinary

---

#  Estructura del proyecto

```
MACETAS
│
├── backend
│   ├── configs
│   ├── controllers
│   ├── middlewares
│   ├── models
│   ├── routes
│   ├── helpers
│   ├── utils
│   ├── database
│   └── app.js
│
├── frontend
│   ├── src
│   │   ├── assets
│   │   ├── components
│   │   ├── context
│   │   ├── hooks
│   │   ├── layouts
│   │   ├── pages
│   │   ├── routes
│   │   ├── services
│   │   └── App.jsx
│   └── package.json
│
└── README.md
```

---

#  Dependencias instaladas

## Backend

```
bcryptjs
cloudinary
cookie-parser
cors
crypto
dotenv
express
jsonwebtoken
mongodb
mongoose
multer
multer-storage-cloudinary
nodemailer
```

## Frontend

```
react
react-dom
react-router-dom
react-router
react-hook-form
react-hot-toast
react-phone-number-input
framer-motion
lucide-react
sweetalert2
tailwind-merge
class-variance-authority
tw-animate-css
@fontsource-variable/geist
shadcn
```

---

#  Instalación

## 1. Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

---

## 2. Instalar dependencias

### Backend

```bash
cd backend
npm install
```

### Frontend

```bash
cd frontend
npm install
```

---

# ▶ Ejecutar el proyecto

## Backend

```bash
npm run dev
```

o

```bash
npm start
```

(según esté configurado)

---

## Frontend

```bash
npm run dev
```

---

#  Variables de entorno

Crear un archivo `.env` dentro del backend.

Ejemplo:

```env
PORT=4000

MONGODB_URI=

JWT_SECRET=

EMAIL_USER=

EMAIL_PASS=

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=
```

---

#  Seguridad

El sistema implementa:

- Contraseñas encriptadas con BcryptJS.
- Autenticación mediante JWT.
- Tokens almacenados en Cookies.
- Validaciones del lado del cliente.
- Validaciones del lado del servidor.
- Protección de rutas privadas.

---

#  Responsive

La aplicación es compatible con:

- Computadoras
- Tablets
- Teléfonos móviles

---

#  Convenciones de nomenclatura

## Archivos

- Componentes → PascalCase

Ejemplo

```
Login.jsx
Register.jsx
Navbar.jsx
```

---

## Variables

Se utiliza **camelCase**

```javascript
userName
profileImage
clientData
```

---

## Funciones

Se utiliza **camelCase**

```javascript
handleSubmit()
updateProfile()
deleteReview()
```

---

## Componentes React

Se utiliza **PascalCase**

```jsx
<Login />
<Navbar />
<Sidebar />
```

---

## Constantes

Cuando aplica:

```javascript
API_URL
MAX_SIZE
JWT_SECRET
```

---

# 👨 Equipo

Proyecto desarrollado como parte del Proyecto Técnico Científico (PTC).

---

#  Licencia

Proyecto desarrollado únicamente con fines académicos.
