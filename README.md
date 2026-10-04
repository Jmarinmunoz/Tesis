# PepsiCo Fleet Management

Plataforma de gestión de flota y taller automotriz desarrollada como proyecto de tesis. Centraliza el ingreso de vehículos, órdenes de trabajo, inventario de repuestos, usuarios por rol y reportes operacionales.

## Demo funcional

Puedes revisar una versión resumida e interactiva del sistema aquí: [Ver TesisDemo](https://pep-example.vercel.app).

La demo permite recorrer las vistas de administrador, supervisor y operador. Usa datos locales del navegador y no está conectada al backend productivo.

## Funcionalidades

- Registro y seguimiento del ingreso de vehículos.
- Órdenes de trabajo y control del estado operativo.
- Inventario y gestión de repuestos.
- Usuarios, autenticación y permisos por rol.
- Dashboard y reportes para apoyar la toma de decisiones.

## Arquitectura

- backend/: API REST con Express y TypeScript.
- frontend/: aplicación React creada con Vite.
- shared/: tipos compartidos entre frontend y backend.

## Tecnologías

| Área | Tecnologías |
| --- | --- |
| Backend | Node.js, Express, TypeScript, Prisma, PostgreSQL |
| Frontend | React, TypeScript, Vite, Tailwind CSS |
| Seguridad | JWT y control de acceso por roles |
| Despliegue | Railway, Vercel y GitHub Actions |

## Ejecución local

1. Clona el repositorio.
2. Instala las dependencias de cada aplicación con npm install.
3. Configura las variables de entorno necesarias para PostgreSQL.
4. Ejecuta frontend y backend según sus respectivos scripts.

## Autores

- Joaquín Marín Muñoz - Ingeniero en Informática.
- Benjamín Vilches - Ingeniero en Informática.

[GitHub de Joaquín](https://github.com/Jmarinmunoz) | [LinkedIn](https://www.linkedin.com/in/joaquin-marin-munoz/)
