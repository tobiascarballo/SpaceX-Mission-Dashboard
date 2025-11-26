# SpaceX Mission Dashboard (SPA - SpaceX)

## 📝 Descripción

Mini Single Page Application que consume la API pública de SpaceX y muestra una lista de lanzamientos. Permite ver detalles de cada lanzamiento (fecha, número de vuelo, detalles, fallas si las hay) y maneja rutas con hash (Home, Launch detail, 404).

---

## 🛠️ Tecnologías y Herramientas

* **Lenguaje:** JavaScript (ES6+)
* **Estructura:** HTML5 / CSS3
* **Entorno:** Node.js (para gestión de dependencias y servidor local)
* **Herramientas de construcción:** Webpack + Babel

## 🚀 Cómo ejecutar el proyecto

Este proyecto utiliza **npm** para gestionar dependencias y el servidor de desarrollo (webpack-dev-server).

### 1. Prerrequisitos
Tener instalado [Node.js](https://nodejs.org/) en tu equipo (incluye npm).

### 2. Instalación y Ejecución

1. **Clonar el repositorio:**
    ```bash
    git clone https://github.com/tobiascarballo/SpaceX-Mission-Dashboard.git
    cd SpaceX-Mission-Dashboard
    ```

2. **Instalar dependencias:**
    ```bash
    npm install
    ```

3. **Iniciar el servidor de desarrollo:**
    ```bash
    npm run dev
    ```
    El servidor de desarrollo está configurado en el puerto 8080 por defecto. Abre tu navegador en http://localhost:8080 si el navegador no se abre automáticamente.

4. **Generar versión de producción (build):**
    ```bash
    npm run build
    ```
    Esto generará la carpeta `dist/` con los archivos listos para desplegar.

## 🧭 Scripts disponibles

* `npm run dev` — Inicia el servidor de desarrollo (webpack-dev-server). 
* `npm run build` — Compila y empaqueta la aplicación para producción.

---

## 📁 Estructura principal del proyecto

Algunos archivos y carpetas importantes:

* `public/index.html` — Plantilla HTML usada por HtmlWebpackPlugin.
* `src/index.js` — Punto de entrada principal.
* `src/pages/` — Páginas (Home, Launch, Error404).
* `src/routes/index.js` — Router hash-based.
* `src/templates/Header.js` — Cabecera de la SPA.
* `src/utils/getData.js` — Lógica para consumir la API pública de SpaceX.
* `src/styles/styles.css` — Estilos globales.

---

## 📷 Capturas de Pantalla
<img width="1919" height="902" alt="image" src="https://github.com/user-attachments/assets/72079430-b6bd-417a-9327-a162dec8b679" />
<img width="1919" height="880" alt="image" src="https://github.com/user-attachments/assets/649e8047-8a14-4ac1-be08-9e813312dd71" />

---

**Desarrollado por Tobías Carballo**
*Estudiante de Licenciatura en Sistemas | UADER*
[LinkedIn](https://www.linkedin.com/in/tobias-carballo/)
