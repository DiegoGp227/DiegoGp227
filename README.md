<div align="center">

# Diego Góngora

### Frontend Developer · React · Next.js · TypeScript

Desarrollo aplicaciones web con foco en **arquitectura, experiencia de usuario, rendimiento y mantenibilidad**.

<p>
  <a href="https://www.linkedin.com/in/diego-gongora-p/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:diego.gp227@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</p>

</div>

---

## 👨‍💻 Sobre mí

Soy desarrollador de software de **Bogotá, Colombia**, enfocado principalmente en el desarrollo **Frontend**.

Mi stack principal gira alrededor de **React, Next.js, TypeScript y Tailwind CSS**, aunque también desarrollo APIs, trabajo con bases de datos y me encargo de la infraestructura cuando el proyecto lo requiere.

Me interesa construir software que no solo funcione, sino que sea **entendible, mantenible y razonable de evolucionar**.

Actualmente estoy profundizando en:

* Arquitectura de software
* Patrones avanzados de React
* TypeScript
* Testing
* Diseño de APIs
* System Design
* Cloud Infrastructure

---

## 🛠️ Stack

### Frontend

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/astro/astro-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="40" />
</p>

`TypeScript` · `JavaScript` · `React` · `Next.js` · `Astro` · `Tailwind CSS`

### Backend

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bun/bun-original.svg" width="40" />
</p>

`Node.js` · `Express` · `Prisma` · `Bun` · `REST APIs` · `Zod`

### Datos & Infraestructura

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cloudflare/cloudflare-original.svg" width="40" />
</p>

`PostgreSQL` · `MySQL` · `Docker` · `Docker Compose` · `Linux` · `Nginx` · `Cloudflare`

### Gestión de proyectos

`Skemap`

---

## 🚀 Proyectos destacados

### 🚴 Crit Virgilio

Plataforma web para la **gestión de competencias de ciclismo**, desarrollada para centralizar el proceso de registro y administración de participantes y reemplazar flujos basados en hojas de cálculo.

El proyecto contempla tanto la experiencia pública para los participantes como herramientas administrativas para la organización.

**Stack:**
`Next.js` `React` `TypeScript` `Node.js` `PostgreSQL` `Prisma` `Docker`

#### Funcionalidades

* Registro de participantes
* Gestión de perfiles y números de competencia
* Clasificación individual y por equipos
* Gestión de categorías
* Panel administrativo
* Selección y gestión de fechas de competencia
* Exportación de registros a Excel
* Gestión centralizada de participantes y resultados

#### Aspectos técnicos

* Arquitectura frontend basada en componentes y módulos.
* API backend para gestionar registros y datos de competición.
* PostgreSQL como sistema de persistencia.
* Prisma como ORM.
* Aplicación y servicios containerizados mediante Docker.
* Despliegue sobre infraestructura propia.

[**Ver repositorio →**](https://github.com/DiegoGp227)
[**Ver proyecto →**](crit-virgilium.devdiego.work)

---

### 🗂️ Skemap — Project Management

Gestor de proyectos full-stack diseñado alrededor de una jerarquía:

```text
Project
└── Epic
    └── Task
        └── Acceptance Criteria
```

Permite organizar proyectos, hacer seguimiento del progreso y gestionar tareas mediante actualizaciones optimistas.

**Stack:**
`Next.js 16` `React 19` `TypeScript` `Express 5` `Prisma 7` `PostgreSQL 16` `Docker`

#### Destacados técnicos

* Actualizaciones **optimistas** con SWR y rollback automático ante errores.
* Contadores sincronizados entre proyectos, epics y tareas sin recargar la página.
* Arquitectura backend separada en **routes → controllers → services → Prisma**.
* Validación con **Zod en todos los boundaries** de la API.
* Verificación de ownership en cada mutación.
* Eliminación en cascada mediante Prisma.
* Entorno de desarrollo completamente containerizado con Docker Compose.

[**Ver repositorio →**](https://github.com/DiegoGp227/skemap)
[**Ver proyecto →**](https://skemap.devdiego.work/auth)

---

### 📈 Fallenway — Habit Tracker

Aplicación full-stack para seguimiento de hábitos con **scheduling flexible, estadísticas y visualización histórica del progreso**.

Los hábitos pueden utilizar diferentes estrategias de frecuencia:

```text
DAILY
SPECIFIC_DAYS
EVERY_N_DAYS
TIMES_PER_WEEK
```

**Stack:**
`Next.js 15` `React 19` `TypeScript` `Express 5` `Prisma 7` `PostgreSQL 16` `Docker`

#### Destacados técnicos

* Motor de frecuencia para determinar los hábitos correspondientes al día actual.
* Cálculos **timezone-aware** basados en la zona horaria del usuario.
* Heatmap estilo GitHub mediante una tabla `DailyContribution` precomputada.
* Lecturas del heatmap en **O(1)** independientemente de la cantidad de historial.
* Estadísticas de progreso y streaks.
* Drag & drop para reorganizar hábitos.
* Subtareas con seguimiento independiente.
* Backend organizado mediante módulos por funcionalidad.
* Autenticación stateless mediante JWT.

[**Ver repositorio →**](https://github.com/DiegoGp227/fallenway)
[**Ver proyecto →**](https://fallenway.devdiego.work/auth)
---

### 🌐 Portfolio

Portfolio personal construido con **Astro**, enfocado en rendimiento, simplicidad y presentación de proyectos.

[**Ver portafolio →**](https://portfolio.devdiego.work/)
**Stack:**
`Astro` `TypeScript` `CSS`

---

## 🧠 Cómo desarrollo

Me interesa resolver problemas desde el diseño hasta el despliegue.

```text
       Entender el problema
                ↓
        Diseñar la solución
                ↓
      Separar responsabilidades
                ↓
       Implementar con tipos
                ↓
     Validar datos y permisos
                ↓
       Optimizar donde importa
                ↓
           Desplegar
```

Al tomar decisiones técnicas intento priorizar:

**Simplicidad → claridad → mantenibilidad → rendimiento**

No considero que una arquitectura sea mejor por tener más capas, abstracciones o tecnologías. La complejidad tiene que estar justificada por el problema.

---

## 📚 Actualmente aprendiendo

* **Software Architecture**
* **System Design**
* **Advanced React**
* **TypeScript**
* **Testing**
* **API Design**
* **Cloud Infrastructure**

---

## 📊 GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=DiegoGp227&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" height="170" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DiegoGp227&layout=compact&hide_border=true&theme=transparent" height="170" />

</div>

---

<div align="center">

### ¿Construimos algo?

<a href="mailto:diego.gp227@gmail.com">Email</a>
  ·   <a href="https://www.linkedin.com/in/diego-gongora-p/">LinkedIn</a>

</div>

<h3 align="left">📊 Contribuciones</h3>
<div align="center">
  <img src="https://ghchart.rshah.org/DiegoGp227" alt="Contribuciones de GitHub" />
</div>

