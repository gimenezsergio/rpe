# RPE Tracker - App de Registro de Esfuerzo Percibido  

## 📌 Descripción  
**RPE Tracker** es una aplicación diseñada para **atletas y entrenadores** que permite registrar entrenamientos utilizando la escala de **RPE (Rating of Perceived Exertion)**. Facilita el seguimiento del progreso, la gestión de equipos y la optimización del rendimiento deportivo.  

## 🔹 Tecnologías utilizadas  
- **Backend:** Node.js, Express.js, Knex.js, MySQL  
- **Frontend:** React (a definir en futuras versiones)  
- **Autenticación:** JWT  
- **Arquitectura:** API REST  

## 💡 Características principales  
✅ Registro de entrenamientos con carga y nivel de RPE.  
✅ Historial de entrenamientos con filtros avanzados.  
✅ Gestión de equipos por parte de entrenadores (opcional).  
✅ Visualización y monitoreo del rendimiento de los atletas.  
✅ Administración de perfiles de usuarios.  

## 📂 Estructura del proyecto  
```bash
/mi-proyecto
│── /backend
│   ├── /src
│   │   ├── /config  (Configuraciones como Knex.js)
│   │   ├── /controllers  (Lógica de negocio)
│   │   ├── /models  (Manejo de datos con Knex.js)
│   │   ├── /routes  (Definición de rutas de la API)
│   │   ├── /middlewares  (Autenticación, logs, etc.)
│   │   ├── /utils  (Funciones auxiliares)
│   ├── package.json
│   ├── knexfile.js
│   ├── server.js
│── /frontend
│   ├── /src  (Componentes y lógica del frontend)
│   ├── package.json
│── .gitignore
│── README.md
