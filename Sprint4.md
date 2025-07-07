# 📅 5.2.4 Sprint 4

## 5.2.4.1. Sprint Planning 4

Aquí se registran los detalles de la planeación del Sprint 4.

| **Sprint #** | Sprint 4 |
|---|---|
| **Sprint Planning Background** | En este sprint se inicia con la implementación del sistema de identidad y autenticación para los usuarios del sistema CustomHost. Se trabajará en el desarrollo de las funcionalidades de Login, Registro de Usuarios y Registro de Hoteles. |
| **Fecha de inicio** | 20/06/2025 |
| **Fecha de finalización** | 03/07/2025 |
| **Duración estimada** | 14 días laborales |
| **Ubicación** | Lima, Reunión virtual por Discord |
| **Preparado por** | SoftCore Team |
| **Participantes (reunión de planificación)** | Arrieta Quispe, Alison Jimena / Ordoñez Ricaldi, Axel Randall / Ccarita Cruz, Brayan Roberto / Santiago Peña, Andreow Jomark / Panta Castro, Fabrizio Martin |
| **Resumen del Sprint n – 1 Review** | Sprint 3: Se desarrolló el backend del sistema utilizando Node.js y Express, integrando seguridad con JWT y logs. Además, se conectó con éxito al frontend y se realizó el despliegue en producción. |
| **Resumen del Sprint n – 1 Retrospective** | Sprint 3: El equipo mostró mayor organización en tareas técnicas. Aunque surgieron algunos desafíos con la integración API-Frontend, se resolvieron rápidamente gracias a una buena comunicación. |
| **Sprint Goal & User Stories** | Implementar el sistema de identidad del usuario (Login y Registro) y el Registro de Hoteles. Estas funcionalidades son esenciales para dar soporte a la administración hotelera futura.<br><br>**Historias de Usuario Relacionadas:**<br>- US44 Iniciar sesión exitosamente *(EP01)*<br>- US45 Registrar como huésped *(EP01)*<br>- US46 Registrarse como hotel *(EP01)*<br>- US47 Iniciar sesión en el sistema *(EP09)*<br>- US48 Registrar un nuevo huésped *(EP09)*<br>- US49 Registrar un nuevo hotel *(EP11)* |
| **Velocidad del Sprint 3** | 18 |
| **Suma de Puntos de Historia** | 25 |

## 5.2.4.2. Aspect Leaders and Collaborators

| Miembro del Equipo        | GitHub Username   | Líder / Colaborador en aspectos claves |
|--------------------------|-------------------|----------------------------------------|
| **Alison Arrieta**       | alisoft08         | Líder en diseño UX/UI para formularios de autenticación |
| **Brayan Ccarita**       | hallzyx           | Líder en desarrollo de funcionalidades IAM |
| **Fabrizio Panta**       | F4brizio24        | Líder en conexión Backend - Frontend |
| **Axel Ordoñez**         | nOOmzzzz          | Desarrollo de lógica de registro de hoteles |
| **Andreow Santiago**     | andrew65411       | Documentación técnica y pruebas funcionales |

## 5.2.4.3. Sprint Backlog 4

![Sprint Backlog 4](Assets/img/Chapter-5/sprint_backlog_4.png)

**Trello Board:** [Sprint 4 Trello](https://trello.com/b/mfzS54R6/customhost-sprint-backlog-4 )

**Tareas Principales:**
- Diseño de interfaces de Login y Registro.
- Implementación del endpoint de registro de usuarios.
- Implementación del endpoint de inicio de sesión con JWT.
- Validación de credenciales y manejo de sesiones.
- Diseño e implementación del formulario de registro de hoteles.
- Integración de registro de hoteles con backend.
- Pruebas unitarias y de integración.
- Documentación técnica y de usuario.
- Actualización del Product Backlog.
- Revisión de cobertura de seguridad en nuevas funcionalidades.

## 5.2.4.4. Development Evidence for Sprint Review

| Repositorio     | Branch                    | Commit Message                          | Committed on (Date) |
|----------------|----------------------------|------------------------------------------|---------------------|
| customhost-backend | develop                | feat: added user registration endpoint with validation | 22/06/2025 |
| customhost-backend | develop                | feat: implemented JWT-based login system | 23/06/2025 |
| customhost-backend | feature/hotel-register | feat: created hotel registration logic | 25/06/2025 |
| customhost-frontend | feature/auth-flow     | feat: designed login and register forms | 24/06/2025 |
| customhost-frontend | develop               | chore: integrated new backend APIs for auth | 27/06/2025 |
| customhost-frontend | feature/hotel-form    | feat: created hotel registration UI | 29/06/2025 |
| customhost-backend | develop               | fix: security improvements on auth routes | 01/07/2025 |
| customhost       | develop                 | docs: updated sprint documentation and API references | 02/07/2025 |

## 5.2.4.5. Execution Evidence for Sprint Review

**Sprint 4:** Durante este sprint se logró implementar las funcionalidades de **identidad de usuario (IAM)**, incluyendo **login**, **registro de usuarios** y el **registro de hoteles**, sentando las bases para la administración hotelera completa en próximos sprints.

**Funcionalidades clave:**

- **Login de Usuarios:**  
  ![Login Page](Assets/img/Chapter-5/sprint_4_%20login.png)

- **Registro de Usuarios:**  
  ![Register Page](Assets/img/Chapter-5/sprint_4_%20register.png)

- **Registro de Hoteles:**  
  ![Hotel Register Page](Assets/img/Chapter-5/sprint_4_%20register_hotel.png)

- **Vista del profile:**
  ![Hotel Register Page](Assets/img/Chapter-5/sprint_4_%20profile.png)


## 5.2.4.6. Services Documentation Evidence for Sprint Review

En este sprint se generaron documentos esenciales relacionados con:

- Estructura de APIs RESTful para autenticación y registro de usuarios/hoteles.
- Endpoints funcionales:
    - `POST /api/users/register`
    - `POST /api/users/login`
    - `POST /api/hotels/register`
- Esquemas de datos en MySQLWorkbench.
- Manejo de tokens y seguridad en endpoints.
- Diagramas C4 Model actualizados para reflejar nuevos componentes.
- Guías de uso para nuevas funcionalidades.

Todo esto fue documentado y revisado durante reuniones diarias del equipo.

## 5.2.4.7. Software Deployment Evidence for Sprint Review

Las funcionalidades desarrolladas en este sprint fueron desplegadas y probadas en entorno de producción. Las herramientas utilizadas incluyen:

- **MongoDB Atlas** para almacenamiento seguro de usuarios y datos de hoteles.
- **Vercel** para el despliegue automático del frontend.
- **GitHub Actions** para CI/CD.
- **Postman** para pruebas de endpoints.

**Resultados del despliegue:**
- Sistema accesible desde cualquier dispositivo.
- Autenticación funcional y segura.
- Registro de usuarios y hoteles operativo.
- Logs activos para monitoreo de errores.
- Protección contra inyecciones y ataques comunes.

**Video del Sprint 4:** 
Link:
https://goo.su/il26a

## 5.2.4.8. Team Collaboration Insights during Sprint

La colaboración durante este sprint fue muy productiva, con un flujo de trabajo bien definido y roles claros. Se utilizaron ramas específicas para cada nueva funcionalidad y se realizaron múltiples revisiones entre pares.

Repositorio principal del backend: https://github.com/SoftCore-App-Web-1ASI0730-2510-4395/customhost-backend 

- **Ramas usadas:**
    - `develop`: rama principal.
    - `feature/user-auth`: para login y registro de usuarios.
    - `feature/hotel-registration`: para registro de hoteles.
    - `fix/security`: ajustes de seguridad en endpoints.

Este flujo de trabajo permitió avanzar de forma rápida y controlada, asegurando calidad, seguridad y escalabilidad del sistema.