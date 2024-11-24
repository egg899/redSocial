# redSocial de Asados

## Descripción del Proyecto
Este proyecto es una plataforma interactiva donde los usuarios pueden:
- Publicar mensajes con texto e imágenes.
- Ver una lista de mensajes publicados por otros usuarios.
- Comentar en mensajes publicados.

El sistema incluye autenticación de usuarios para asegurar que cada mensaje esté asociado con un autor registrado.

---

## Funcionalidades Implementadas
1. **Autenticación de Usuarios:**
   - Inicio de sesión y cierre de sesión utilizando Firebase Authentication.

2. **Publicación de Mensajes:**
   - Formulario para enviar mensajes con campos de texto e imágenes.
   - Subida de imágenes a Cloudinary.
   - Almacenamiento de mensajes en Firestore.

3. **Listado de Mensajes:**
   - Visualización de los mensajes enviados por los usuarios.
   - Muestra de imágenes asociadas con los mensajes.

4. **Comentarios en Mensajes:**
   - Formulario para añadir comentarios a los mensajes.
   - Visualización de comentarios en tiempo real.

5. **Suscripción en Tiempo Real:**
   - Actualización automática de mensajes y comentarios a través de Firebase Firestore.

---

## Tecnologías Utilizadas
### Backend
- **Firebase Firestore:** Base de datos para almacenamiento en tiempo real.
- **Cloudinary:** Almacenamiento de imágenes en la nube.

### Frontend
- **Vue.js:** Framework para la creación de interfaces de usuario.
- **Tailwind CSS:** Framework CSS para diseño responsivo y estilización.
- **Vite:** Herramienta de desarrollo para proyectos con Vue.js.

---

## Instalación y Configuración
### Requisitos Previos
- Node.js (v16 o superior)
- npm (o yarn)

### Comandos de Instalación
1. Clonar el repositorio:
   git clone https://github.com/egg899/redSocial.git

2. Entrar al directorio del proyecto:

    cd tu-repositorio
3. Instalar dependencias:
npm install
npm install vue-router@4
npm install firebase
npm install cloudinary
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init



