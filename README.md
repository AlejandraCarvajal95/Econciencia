# 🌍 eConsciencia

**eConsciencia** es una plataforma educativa interactiva diseñada para sensibilizar, educar y evaluar conocimientos sobre los desafíos ambientales más críticos que enfrenta el agua en nuestro planeta. Este proyecto combina experiencias visuales enriquecidas, simulaciones 3D y cuestionarios dinámicos para ofrecer un aprendizaje inmersivo.

---

## 👥 Proyecto Académico y Colaborativo

Este software fue desarrollado como parte del **Proyecto Integrador** escolar en colaboración con compañeros de curso. 

* **Contexto:** Trabajo en equipo para la materia académica correspondiente.
* **Propósito:** Demostrar habilidades de desarrollo frontend moderno, interactividad en 3D, y manejo de persistencia en la nube mediante un enfoque pedagógico sobre el cuidado del agua.

---

## 🚀 Características Principales

La plataforma se compone de diversos módulos interactivos:

1. **💧 Escasez de Agua (Water Shortage):** Sección informativa sobre el impacto del estrés hídrico global, sequías y el agotamiento de fuentes de agua potable.
2. **🗑️ Contaminación del Agua (Water Contamination):** Una simulación interactiva construida en **3D** utilizando físicas avanzadas, donde se recrea un entorno interactivo de bloques para comprender cómo la contaminación afecta los cuerpos de agua.
3. **🧪 Acidificación del Agua (Water Acidification):** Explicación interactiva sobre los efectos de la disolución de dióxido de carbono ($CO_2$) en mares y océanos y la consecuente caída del pH.
4. **🧠 Quiz interactivo:** Cuestionario con retroalimentación en tiempo real para poner a prueba los conceptos aprendidos sobre el cuidado del agua.
5. **🔐 Sistema de Autenticación:** Registro y login de usuarios integrados con **Firebase Auth** para gestionar el progreso.

---

## 🛠️ Stack Tecnológico

* **Frontend:** [React](https://react.dev/) + [Vite](https://vitejs.dev/)
* **Estilos y Componentes:** [Tailwind CSS](https://tailwindcss.com/) & [Shadcn UI](https://ui.shadcn.com/) (Radix UI)
* **Entorno 3D y Físicas:** 
  * [Three.js](https://threejs.org/)
  * [@react-three/fiber](https://r3f.docs.pmnd.rs/) (R3F)
  * [@react-three/drei](https://github.com/pmndrs/drei)
  * [@react-three/rapier](https://github.com/pmndrs/react-three-rapier) (Físicas 3D en tiempo real)
* **Gestión de Estado:** [Zustand](https://github.com/pmndrs/zustand)
* **Base de Datos y Autenticación:** [Firebase](https://firebase.google.com/) (Firestore & Auth)

---

## 💻 Instrucciones para Ejecución Local

Para clonar y correr este proyecto en tu computadora, sigue estos pasos:

### Prerrequisitos
Asegúrate de tener instalado [Node.js](https://nodejs.org/) (versión 18 o superior recomendada).

### 1. Clonar el repositorio
```bash
git clone <URL-DE-TU-REPOSITORIO>
cd <nombre-de-la-carpeta>
```

### 2. Instalar dependencias
Navega a la carpeta de la aplicación e instala los paquetes necesarios:
```bash
cd eConsciencia
npm install
```

### 3. Configurar variables de entorno
Crea un archivo `.env` en la raíz de la carpeta `eConsciencia` con tus credenciales de Firebase (puedes crear un proyecto de prueba gratis en la consola de Firebase):
```env
VITE_FIREBASE_API_KEY=tu_api_key
VITE_FIREBASE_AUTH_DOMAIN=tu_auth_domain
VITE_FIREBASE_PROJECT_ID=tu_project_id
VITE_FIREBASE_STORAGE_BUCKET=tu_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=tu_messaging_sender_id
VITE_FIREBASE_APP_ID=tu_app_id
```

### 4. Ejecutar el servidor de desarrollo
Inicia la aplicación de manera local:
```bash
npm run dev
```
Abre tu navegador en `http://localhost:5173`.
