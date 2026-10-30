<h1 align="center">Michael Enciso Yancce</h1>

<p align="center">
  <b>Ingeniero de software con IA · Sistemas, flujos y automatización</b><br>
  Diseño y construyo sistemas empresariales, APIs y flujos que funcionan de punta a punta, y los pruebo.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/.NET_Core-512BD4?logo=dotnet&logoColor=white" alt=".NET Core">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker">
</p>

<p align="center">
  📍 Andahuaylas, Apurímac, Perú ·
  <a href="mailto:michaelencisoyancce@gmail.com">michaelencisoyancce@gmail.com</a> ·
  📱 +51 931 568 537 ·
  <a href="https://linkedin.com/in/enciso-michael">LinkedIn</a>
</p>

---

## Sobre mí

Soy desarrollador de software y me dedico a construir sistemas y flujos de trabajo: desde la API y las reglas de negocio hasta las integraciones y automatizaciones que los conectan. Trabajo con ERPs multi-tenant en Laravel y .NET Core, asistentes de IA conectados a herramientas reales con permisos por usuario, y procesos que conectan plataformas como Google Sheets y Moodle. Me importa que lo que construyo se pueda probar: pruebo los casos límite y los errores antes de entregar. Busco posiciones remotas en sistemas, backend e IA aplicada.

## Qué hago

- **Sistemas y APIs empresariales:** APIs RESTful con JWT, arquitectura en capas, SOLID y DDD, sobre ERPs multi-tenant.
- **Flujos y automatización:** procesos en segundo plano, integraciones entre sistemas y automatizaciones sobre Google Sheets y Moodle.
- **IA aplicada:** asistentes LLM con tool calling, contexto por módulo y verificación de permisos antes de ejecutar cualquier acción.
- **Testeo y calidad:** pruebas unitarias y automatizadas, y planificación de casos límite y escenarios de error (por ejemplo, qué debe hacer el asistente de IA ante operaciones no permitidas o fallos de ejecución).

## Stack

| Área | Tecnologías |
|---|---|
| Backend | PHP, Laravel, C#, ASP.NET Core, ASP.NET Boilerplate (ABP), Java, Spring Boot |
| Frontend | TypeScript, JavaScript, React, Vue.js, HTML, CSS, jQuery, Bootstrap |
| Datos e integración | MySQL, PostgreSQL, SQLite, Eloquent ORM, APIs RESTful, JWT, Google Sheets, Moodle |
| Testeo y calidad | Pruebas unitarias, pruebas automatizadas, casos límite y escenarios de error, Postman, Testcontainers, documentación técnica |
| Arquitectura | Multi-tenant, SOLID, MVC, DDD, hexagonal, microservicios, procesos en segundo plano, refactorización |
| IA | Integración de LLMs por API, tool calling, permisos de ejecución, manejo de tokens, parámetros de generación, RAG |
| Herramientas | Git, GitHub, Docker, Postman, Visual Studio Code |

## Experiencia

**Kimen** · Automatización y soporte de sistemas · *Abr. 2025 – Actualidad*
Automatizo el envío de correos desde Google Sheets, integro una API externa con Moodle para verificar calificaciones, doy soporte a usuarios y mantengo sitios WordPress.

**Geor Fábrica de Software S.A.C.** · Backend e IA aplicada (por proyecto) · *Feb. 2025 – Mar. 2025*
Implementé un asistente LLM en Laravel conectado por API a herramientas de un ERP multi-tenant, enfocado en facturación. Se invoca con menciones en comentarios, limita las herramientas según módulo y permisos del usuario, reutiliza la autorización existente y contempla casos límite y errores de ejecución. Planifiqué los casos límite y escenarios de error para definir cómo responde el asistente ante operaciones no permitidas y fallos. Estado: desplegado en servidor de pruebas; la publicación en producción depende de Geor.

**Geor Fábrica de Software S.A.C.** · Desarrollador Backend · *Jul. 2023 – Feb. 2025 · Remoto*
APIs RESTful para un ERP multi-tenant con Laravel (SOLID, MVC, MySQL, Eloquent), un microservicio integrado por JWT con procesos en segundo plano, y APIs con .NET Core y ABP en N capas y DDD, con documentación y apoyo en integraciones con Vue.js.

**D & Arkam S.A.C.** · Desarrollador Backend · *Ene. 2023 – Jun. 2023*
Aplicación de gestión de productos con paneles de control en PHP, Laravel y MySQL, y APIs documentadas con JWT.

**Jhardsystex** · Desarrollador Full-Stack · *Ago. 2022 – Dic. 2022 · Remoto*
Sistema contable de ingresos y egresos con PHP, JavaScript y MySQL, interfaces con jQuery y Bootstrap, y diagramas UML.

## Educación

**SENATI, sede Lima Independencia** · Ingeniería de Software con Inteligencia Artificial · *2020 – 2023*

## Proyectos personales

### Nexo · aplicación de escritorio

Aplicación de escritorio para organizar mi día a día, hecha con **React, TypeScript y Electron**, con base de datos local **SQLite (Drizzle ORM)**. Los datos quedan en mi equipo, con exportación y copias automáticas.

- **Tareas:** tablero, contextos, proyectos, prioridades, cronómetro, historial, captura rápida y búsqueda sin distinguir tildes ni mayúsculas.
- **Gym:** entrenamientos, rutinas, catálogo, medidas e historial con análisis de progreso.
- **CV:** perfil, experiencia, preparación para ofertas y seguimiento de postulaciones.
- **Mensajes:** plantillas por categoría y canal, con variables y copia del texto listo.
- **Testeo y calidad:** pruebas automatizadas y lint como parte del flujo de desarrollo, y documentación de diagnóstico, criterios de aceptación y decisiones del producto.
- Funciones de IA opcionales (se configuran aparte).

`React` `TypeScript` `Electron` `SQLite` `Drizzle`

### pdf-rag · proyecto de aprendizaje

Proyecto para aprender y entender el proceso y el flujo de un sistema **RAG sobre documentos PDF** (Retrieval-Augmented Generation). Base backend en **Java 21 y Spring Boot 3** con **PostgreSQL** (Docker Compose), seguridad con Spring Security y OAuth2 resource server, validación, y preparado para pruebas de integración con Testcontainers.

`Java` `Spring Boot` `PostgreSQL` `RAG` `Docker` `Testcontainers`
