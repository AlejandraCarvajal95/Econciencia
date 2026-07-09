# 🌍 eConsciencia

**eConsciencia** is an interactive 3D web prototype designed for environmental education and water conservation awareness. This website serves as an MVP (Minimum Viable Product) developed collaboratively for a university project, focusing primarily on the integration of interactive three-dimensional environments and modern frontend technologies.

🔗 **[Live Demo on Vercel](https://econciencia.vercel.app)**

---

## 📸 Screenshots

| Home (3D World) | Acidification Section |
| :---: | :---: |
| ![Home](./screenshots/inicio.png) | ![Acidification](./screenshots/acidificacion.png) |

| Contamination Section | Marine Sensitization |
| :---: | :---: |
| ![Contamination](./screenshots/contaminacion.png) | ![Sensitization](./screenshots/sensibilizacion.png) |

> *Note: To display the images correctly on GitHub, save your screenshots inside a folder named `screenshots` at the root of this repository with the corresponding names (`inicio.png`, `acidificacion.png`, etc.).*

---

## 🛠️ Key Technologies

* **3D Design & Interactivity:** Three.js, `@react-three/fiber` (R3F), `@react-three/drei`, and 3D physics with `@react-three/rapier`.
* **Frontend:** React + Vite, Tailwind CSS, Zustand (state management), and Radix UI.
* **Authentication:** Firebase Auth.

---

## ✍️ My Contribution

Within the development team, my main responsibilities were:
* **Acidification Section:** Built and integrated the interactive 3D scene that demonstrates the impact of $CO_2$ on the ocean.
* **Quiz Design:** Collaborated on designing the interactive quiz section, including developing the element selection logic.
* **Backend & Auth Integration:** Configured and integrated **Firebase Authentication** to manage user access and state.
* **DevOps & Deployment:** Set up the production pipeline and successfully deployed the application on **Vercel**.

---

## 💻 Local Setup

Follow these steps to run the prototype on your local machine:

### 1. Clone the repository and navigate to the project directory
```bash
git clone <YOUR-REPOSITORY-URL>
cd eConsciencia
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure environment variables (Firebase Auth)
Create a `.env` file in the root of the `eConsciencia` folder with your Firebase credentials:
```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### 4. Start the local development server
```bash
npm run dev
```
The application will be available at `http://localhost:5173`.
