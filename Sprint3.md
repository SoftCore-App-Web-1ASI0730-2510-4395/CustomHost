### 5.2.3 Sprint 3

#### 5.2.3.1. Sprint Planning 3

A continuación, se presenta el planificación detallada del Sprint 3, centrado en el desarrollo técnico y la integración del backend con el frontend previamente construido.

| **Sprint #** | Sprint 3 |
|---|---|
| **Sprint Planning Background** |                                  |
| **Fecha de inicio** | 08/06/2025 |
| **Fecha de finalización** | 19/06/2025 |
| **Duración estimada** | 12 días laborales |
| **Ubicación** | Lima, Reunión virtual por Discord |
| **Preparado por** | SoftCore Team |
| **Participantes (reunión de planificación)** | Arrieta Quispe, Alison Jimena / Ordoñez Ricaldi, Axel Randall / Ccarita Cruz, Brayan Roberto / Santiago Peña, Andreow Jomark / Panta Castro, Fabrizio Martin |
| **Revisión de entregables anteriores** | Sprint 1: Desarrollo de la landing page<br>Sprint 2: Implementación del frontend funcional |
| **Resumen del Sprint n – 1 Retrospective** | Sprint 2: Se validó la importancia de un diseño UX/UI sólido y se avanzó significativamente en componentes visuales, pero se identificó la necesidad de desarrollar e integrar funcionalidades técnicas mediante un backend robusto. |

**Objetivo del Sprint 3:** Desarrollar el backend del sistema CustomHost utilizando buenas prácticas de arquitectura modular, seguridad y logs, asegurando su conexión efectiva con el frontend existente. Este sprint también incluyó preparación de guiones para entrevistas de validación y grabación del video "About the Product".

#### 5.2.3.2. Aspect Leaders and Collaborators

| Miembro del Equipo        | GitHub Username   | Líder / Colaborador en aspectos claves |
|--------------------------|-------------------|----------------------------------------|
| **Axel Ordoñez**         | nOOmzzzz          | Líder en diseño de guiones de entrevista |
| **Fabrizio Panta**       | F4brizio24        | Líder en integración Backend-Frontend |
| **Brayan Ccarita**       | hallzyx           | Despliegue y verificación del backend |
| **Alison Arrieta**       | alisoft08         | Configuración de backend siguiendo buenas prácticas |
| **Andreow Santiago**     | andrew65411       | Desarrollo inicial del backend, documentación y entrega final del informe |

#### 5.2.3.3 Sprint Backlog 3

![Sprint Backlog 3](Assets/img/Chapter-5/sprint%20backlog%203.png)

**Link del trello:** [sprint backlog 3 trello](https://trello.com/b/mfzS54R6/customhost-sprint-backlog-3)

**Tareas Principales:**

- Diseño de guiones para entrevistas de validación.
- Desarrollo inicial del backend del sistema.
- Configuración del backend aplicando buenas prácticas (seguridad, logs).
- Integración exitosa del backend con el frontend existente.
- Análisis y síntesis de resultados de entrevistas de validación.
- Deploy del backend a servidor de producción.
- Actualización de diagramas C4 model.
- Mejoras en User Stories y Product Backlog.
- Incorporación de comentarios del docente al informe final.
- Revisión general y entrega final del informe.

#### 5.2.3.4. Development Evidence for Sprint Review

En esta seccion se incluyen los commits realizados a los repositorios de la organizacion de Github. Mencionamos tambien los links de los repositorios de la organizacion de Github.

Landing Page: https://github.com/SoftCore-App-Web-1ASI0730-2510-4395/AppWeb-landing-page

Frontend: https://github.com/SoftCore-App-Web-1ASI0730-2510-4395/customhost-frontend

Backend: https://github.com/SoftCore-App-Web-1ASI0730-2510-4395/customhost-backend

| Repositorio | Rama | Mensaje del commit | Fecha |
|------------|------|--------------------|-------|
| customhost-backend | develop | feat: initial backend structure using Node.js and Express | 14/06/2025 |
| customhost-backend | develop | feat: security implementation with JWT and logging | 16/06/2025 |
| customhost-backend | develop | fix: logic improvements based on feedback | 17/06/2025 |
| customhost-backend | develop | deploy: production server deployment | 17/06/2025 |
| customhost-frontend | develop | chore: integrate backend API endpoints | 17/06/2025 |
| customhost | develop | docs: updated mockups and wireframes | 18/06/2025 |
| customhost | develop | chore: incorporate teacher comments into final report | 18/06/2025 |
| customhost | develop | docs: final report revision and delivery | 19/06/2025 |

Estos commits reflejan el trabajo técnico constante y distribuido entre todos los miembros del equipo, enfocado en el backend, integración con frontend, despliegue y revisión final del informe.

#### 5.2.3.5. Execution Evidence for Sprint Review

- **Backend Funcional:** Se implementó la lógica principal del sistema utilizando Node.js, con enfoque en seguridad (JWT), registro de logs y modularidad.
- **Integración Exitosa:** El backend fue conectado al frontend desarrollado en el Sprint 2, permitiendo comunicación efectiva entre ambas capas del sistema.
- **Despliegue a Producción:** El backend fue desplegado en un servidor de producción, garantizando disponibilidad para pruebas reales.
- **Entrevistas de Validación:** Se realizaron entrevistas con huéspedes y staff hotelero para validar funcionalidades y obtener retroalimentación real sobre el producto.
- **Video Institucional:** Se produjo el video "About the Product" y "About the Team", disponibles en SharePoint.

URL del sistema funcional (Frontend + Backend): <https://customhost-app.vercel.app/guest-home>

#### 5.2.3.6. Services Documentation Evidence for Sprint Review

Durante este sprint se avanzó en la implementación técnica del sistema, por lo que se generaron documentos esenciales relacionados con:

- Estructura de APIs RESTful.
- Endpoints funcionales para gestión de usuarios, reservas, preferencias y dispositivos IoT.
- Documentación técnica del backend y su configuración segura.
- Diagramas C4 Model actualizados.
- Guiones para entrevistas de validación de usuario.

Todo esto se complementó con el análisis de resultados obtenidos en las entrevistas de validación y su aplicación directa al diseño final del sistema.

#### 5.2.3.7. Software Deployment Evidence for Sprint Review

El backend fue desplegado en un entorno de producción, utilizando herramientas profesionales y buenas prácticas:

- Herramientas utilizadas:

  - Node.js para el desarrollo del backend.
  - Express para crear los endpoints REST.
  - MongoDB Atlas como base de datos en la nube.
  - GitHub Actions para CI/CD.
  - Render o Railway para despliegue en producción.

###

- Resultados del despliegue:
  - Sistema operativo y accesible desde cualquier dispositivo.
  - Comunicación estable con el frontend.
  - Logs funcionales y monitoreo de errores activo.
  - Seguridad implementada con token JWT y protección contra inyecciones.

Video del Sprint 3: [sprint 3 - video](https://upcedupe-my.sharepoint.com/personal/u202317362_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202317362_upc_edu_pe%2FDocuments%2Fvideo2798432421%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E3e0a06d8-3cbe-4574-9316-b337c5788c56&isDarkMode=true)

#### 5.2.3.8. Team Collaboration Insights during Sprint

La dinámica colaborativa durante el Sprint 3 fue muy activa, con roles bien definidos y participación constante de todos los miembros del equipo: [Repositorio Backend](https://github.com/SoftCore-App-Web-1ASI0730-2510-4395/customhost-backend)


- **Commits frecuentes y distribuidos:**  
  ![Commits Sprint 3](Assets/img/cover/TB1%20commits.png)

- **Network Graph:**  
  ![Network Graph Sprint 3](Assets/img/cover/network-tb2-backend.png)

- **Ramas usadas:**
   - `develop`: rama principal.
   - `feature/backend-security`: para configuración de seguridad.
   - `feature/integration`: para conectar backend con frontend.
   - `fix/user-stories`: ajustes basados en feedback técnico.

Este flujo de trabajo permitió un desarrollo ordenado, controlado y orientado a calidad, escalabilidad y mantenimiento futuro del sistema.

