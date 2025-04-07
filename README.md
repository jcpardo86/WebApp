
# 📊 RINGANA WebApp

Aplicación web para gestión de ventas, metas, recursos y seguimiento comercial, desarrollada con HTML, JavaScript, TailwindCSS y Firebase.

## 🚀 Funcionalidades

- Registro de ventas con seguimiento automático
- Gestión de productos, clientas, bonos y periodos
- Visualización de metas y progreso
- Autenticación con Google y control de roles (admin/usuario)
- Sincronización automática con Firebase Firestore
- Copias de seguridad locales y exportaciones CSV
- Interfaz optimizada para móviles

## 🗂 Estructura del proyecto

```
/
├── index.html              # Página de inicio (dashboard)
├── pages/                  # Vistas separadas por módulo
├── js/                     # Scripts por módulo y funciones compartidas
├── css/                    # Estilos personalizados
├── assets/                 # Imágenes y recursos estáticos
└── README.md
```

## 🔧 Cómo editar y probar

1. Abre el proyecto en **Visual Studio Code**.
2. Instala la extensión **Live Server**.
3. Haz clic derecho en `index.html` y elige "Open with Live Server".
4. Edita el contenido desde los archivos HTML o JS.
5. Firebase está preconfigurado y se conecta automáticamente.

## 🌐 Publicar en GitHub Pages

1. Crea un nuevo repositorio en GitHub.
2. Sube el contenido de esta carpeta (no subcarpetas anidadas).
3. Ve a `Settings > Pages` y selecciona rama `main` y carpeta `/root`.
4. Accede a tu app en `https://tuusuario.github.io/nombre-repo`.

## 🔐 Firebase

- El proyecto incluye autenticación con Google.
- Firestore es utilizado como base de datos.
- Los datos se sincronizan con localStorage para acceso offline.

## 📦 Librerías externas

- [Tailwind CSS](https://tailwindcss.com/)
- [Firebase Web SDK](https://firebase.google.com/)
- [Chart.js](https://www.chartjs.org/)
- [Toastify.js](https://apvarun.github.io/toastify-js/)

---

© 2025 - Proyecto Ringana
