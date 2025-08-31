# Proyecto PERN

Este proyecto utiliza el stack **PERN** (PostgreSQL, Express, React y Node.js) con la base de datos desplegada en **Render**.

## 🚀 Tecnologías

* **Frontend:** React + Vite 
* **Backend:** Node.js + Express
* **Base de datos:** PostgreSQL (hosteada en Render)

---

## 📦 Requisitos previos

Asegúrate de tener instalado en tu máquina:

* [Node.js](https://nodejs.org/) version 21.1.7
* [npm](https://www.npmjs.com/) 

---

## ⚙️ Configuración del proyecto

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/usuario/mi-proyecto-pern.git
   cd mi-proyecto-pern
   ```

2. **Instalar dependencias en el backend**

   ```bash
   cd examen-server-pern
   npm install
   ```

3. **Configurar variables de entorno para el backend**
   Crea un archivo `.env` dentro de la carpeta `backend` con la siguiente estructura:

   ```env
   PORT=4000
   DATABASE_URL=postgresql://usuario:password@host:puerto/nombrebasedatos
   ```

   El `DATABASE_URL` se obtiene desde Render en la sección de tu base de datos.

4. **Levantar el backend**

   ```bash
   npm run dev
   ```

5. **Instalar dependencias en el frontend**

   ```bash
   cd ../examen-cliente-pern
   npm install
   ```
   
6. **Levantar el frontend**

   ```bash
   npm run dev
   ```

---

## ▶️ Ejecución

* El **backend** estará disponible en `http://localhost:4000`
* El **frontend** estará disponible en `http://localhost:5173`
* La **Documentacion** de Swagger estara disponible en `http://localhost:4000/docs`

---

## 📖 Scripts útiles

### Backend

* `npm run dev` → Levanta el servidor con nodemon
* `npm run test` → Ejecuta las pruebas
* `npm run test:coverage` → Ejecuta pruebas de cobertura 

### Frontend
* `npm run dev` → Levanta la app en desarrollo
