# 🎮 MonedAventura — Plataforma Educativa Gamificada

MonedAventura es una plataforma educativa gamificada diseñada para enseñar finanzas personales a niños mediante misiones interactivas, economía virtual y desafíos prácticos.  
Su objetivo es promover el aprendizaje financiero de manera divertida, intuitiva y accesible.

---

## 🚀 Tecnologías Utilizadas

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-State%20Management-blue?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?style=for-the-badge&logo=docker)
![Django](https://img.shields.io/badge/Django-REST%20API-092E20?style=for-the-badge&logo=django)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-336791?style=for-the-badge&logo=postgresql)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-Design-black?style=for-the-badge&logo=figma)

## 💡 Enfoque del Proyecto

Este proyecto prioriza:
- Arquitectura modular y escalable
- Buen manejo de estado en frontend
- Separación clara de responsabilidades
- Integración frontend–backend vía API REST
- Experiencia de usuario enfocada en público infantil

### **Resumen técnico**
- Frontend: React (Vite) + TypeScript + TailwindCSS  
- Estado global: Zustand  
- Backend (arquitectura implementada en Sprint 2): Django REST Framework  
- Base de datos: PostgreSQL  
- Contenerización: Docker + Docker Compose  
- Diseño UI/UX: Figma  
- Control de versiones: Git + GitHub

---

## 📘 Descripción General del Proyecto

MonedAventura enseña conceptos esenciales de educación financiera para niños de forma interactiva:

- Misiones educativas basadas en historias  
- Sistema de monedas virtuales  
- Recompensas y logros  
- Panel parental con métricas  
- Flujo educativo progresivo por niveles  
- Integración con API REST  
- Interfaz con enfoque infantil (8–12 años)

---

## 🧩 Funcionalidades Principales

- 🪙 **Sistema económico virtual:** recompensas, monedas y administración de ahorro  
- 🧠 **Misiones gamificadas:** niveles formativos, minijuegos y feedback  
- 🚀 **Progresión educativa:** desbloqueo de niveles y logros  
- 👨‍👩‍👧 **Panel Parental:** monitoreo del avance y estadísticas del niño  
- 🧱 **Arquitectura modular:** componentes reutilizables y organizados  
- 🔌 **Integración con API:** fetch de metas, misiones, progreso y logros  
- 📱 **Diseño responsivo:** optimizado para móvil, tablet y desktop

---

## 📁 Estructura del Proyecto

MonedAventura/
│── components/ # Componentes reutilizables
│── data/ # Datos estáticos
│── services/ # Conexión API y servicios externos
│── views/ # Vistas principales del frontend
│── App.tsx # Punto principal de la aplicación
│── index.tsx # Render inicial
│── index.html # HTML base
│── types.ts # Tipado global
│── tsconfig.json # Configuración TypeScript
│── vite.config.ts # Configuración de Vite
│── package.json # Dependencias del proyecto
│── README.md # Documentación del proyecto

yaml
Copiar código

---

## 🔌 Variables de Entorno

Usa un archivo `.env.local` con:

VITE_API_URL=http://localhost:8000

yaml
Copiar código

El repositorio incluye un `.env.example` listo para copiar.

---

## 🧪 Instalación y Ejecución

### **1. Instalar dependencias**
```bash
npm install
2. Ejecutar en desarrollo
bash
Copiar código
npm run dev
3. Construir para producción
bash
Copiar código
npm run build
📸 Capturas de Pantalla
Una vez agregues tus imágenes en docs/screenshots/, puedes mostrarlas así:

md
Copiar código
![Inicio](docs/screenshots/home.png)
![Nivel](docs/screenshots/level.png)
![Panel Parental](docs/screenshots/parent-dashboard.png)

🎯 Contexto del Proyecto

MonedAventura es un proyecto de desarrollo completo orientado a la creación
de una plataforma educativa gamificada para la enseñanza de finanzas personales
en niños.

El proyecto fue desarrollado como trabajo de cierre de carrera, aplicando
buenas prácticas de desarrollo frontend, arquitectura web, integración de APIs
y diseño centrado en el usuario.

👨‍💻 Autor
Kevin Ortega  
Ingeniero en Informática  

📧 Email: kevin.ortega.p24@gmail.com  
🔗 GitHub: https://github.com/kevinortega-dev  
🔗 LinkedIn: https://www.linkedin.com/in/kevin-ortega-3-55379225/
