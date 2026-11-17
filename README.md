<h1 align="center">Cesar Camacho Duran</h1>

<p align="center">
  <strong>Desarrollador fullstack</strong> · TypeScript, Next.js, Fastify, PostgreSQL<br>
  Pruebas, integración continua y seguridad desde el diseño · Santa Cruz de la Sierra, Bolivia
</p>

<p align="center">
  <a href="https://runer0101.github.io"><img src="https://img.shields.io/badge/Portafolio-00b86b?style=for-the-badge&logo=safari&logoColor=white" alt="Portafolio"></a>
  <a href="mailto:ccamachod6@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/cesar-camacho-duran-305579362/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

## Qué construyo

Aplicaciones web completas: esquema de base de datos, permisos en el servidor, interfaz y despliegue. Lo que me distingue no es el framework, sino lo que queda detrás: una garantía en la base de datos, una prueba que la demuestra y un pipeline que la vigila.

### [Event-Roll](https://github.com/runer0101/Event-Roll) — control de acceso en vivo para eventos

Importación de invitados desde Excel, un código por ayudante con permisos individuales y marcado de entradas en tiempo real. **El check-in es atómico**: dos guardias sobre el mismo invitado producen una sola entrada, garantizado por la base de datos y no por el código de la aplicación.
`Next.js 16 · Prisma · PostgreSQL · 54 pruebas · CI con typecheck, lint y e2e` · [demo](https://event-roll.vercel.app)

### [canchas-api](https://github.com/runer0101/canchas-api) — reservas que no pueden solaparse

Backend puro. Dos reservas activas de la misma cancha no pueden coexistir: lo impone un `exclusion constraint` de PostgreSQL sobre `tstzrange`, así que dos peticiones simultáneas reciben una reserva y un `409`, sin ventana entre la lectura y la escritura.
`Fastify · TypeScript · Zod · OpenAPI · 20 pruebas`

### [simulador-circuitos-malla](https://github.com/runer0101/simulador-circuitos-malla) — cálculo de mallas de Kirchhoff

Resuelve las corrientes y verifica la ley de tensiones malla por malla, con el circuito dibujado. Dos implementaciones equivalentes (Python como oráculo, Rust como servicio) con paridad numérica probada a 1e-9.
`Rust · axum · Docker · 54 pruebas · despliegue en Render` · [demo](https://simulador-circuitos-malla.onrender.com)

## Especialidad y herramientas

Cada área empieza por lo que uso a diario; debajo queda lo que he trabajado sin ser mi centro.

**Frontend** — Especialidad: **Next.js** y **Vue.js**
También he trabajado con: TypeScript · React · JavaScript · Tailwind · Vite · HTML/CSS

**Backend** — Especialidad: **Node.js** y **Python**
También he trabajado con: TypeScript · Fastify · Rust · Express · Laravel · PHP

**Datos** — Especialidad: **PostgreSQL**
También he trabajado con: MySQL · Prisma · migraciones versionadas

**Entrega** — Especialidad: **Docker** y **GitHub Actions**
También he trabajado con: Linux · Nginx · Git · Vercel · Render · fundamentos de AWS

**Pruebas** — Especialidad: **Vitest** y **Playwright**
También he trabajado con: PHPUnit · cargo test

**Seguridad** — Especialidad: **OWASP Top 10** y **autorización por rol y por inquilino**
También he trabajado con: auditoría de dependencias · revisión con informe de severidad · contraseñas y sesiones · validación en el servidor

## Cómo trabajo

- **Pruebas primero** cuando el comportamiento cambia; sin rojo observado no hay verde creíble.
- **La garantía vive en el dato, no en el código**: restricciones, claves y permisos en la base de datos.
- **Nada se declara que no se pueda sostener**: cada cifra de estos repositorios sale de su propio CI.

---

<sub>Fullstack developer based in Santa Cruz de la Sierra, Bolivia. I build web applications end to end, with database-enforced guarantees, tests and CI — not with promises in the README.</sub>
