<div align="center">

# Juan Pablo Linares Laverde
### Software Engineer | Full-Stack, Cloud Architecture & Engineering Quality

<p align="center">
  <a href="https://github.com/PabloLinares06">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=2800&pause=1200&color=38BDF8&center=true&vCenter=true&width=620&lines=Software+Engineer+%7C+Full-Stack+Developer;.NET+Core+%7C+Angular+%7C+NestJS+%7C+PostgreSQL;Agile+%2F+Scrum+%7C+DoR+%26+DoD+%7C+IEEE+730+%2F+ISO+29119;Cloud+FinOps+%7C+Multi-Tenant+Architectures;ERP+Integrations+%7C+Colombian+Labor+Compliance" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/jplinaresdev"><img src="https://img.shields.io/badge/LinkedIn-jplinaresdev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:juanpalinare@gmail.com"><img src="https://img.shields.io/badge/Email-juanpalinare%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Ubicación-Medellín%2C%20Colombia-0ea5e9?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Medellín, Colombia" />
</p>

---

</div>

## Sobre Mí

Desarrollador de Software con experiencia práctica en la construcción de aplicaciones modernas, escalables y orientadas a la alta calidad, tanto en **entornos empresariales (.NET / C#)** como en **soluciones full-stack nativas de nube (Angular, NestJS, PostgreSQL)**.

Especializado en el diseño de **APIs REST robustas**, **arquitectura de software (Hexagonal / DDD)**, **optimización de costos de infraestructura (Cloud FinOps)** y la aplicación rigurosa de **metodologías ágiles (Scrum)** con estándares formales de calidad y documentación técnica (**IEEE 730 / ISO/IEC/IEEE 29119**). Capacidad comprobada para traducir requerimientos normativos y de negocio complejos —incluyendo **lógica de nómina bajo la legislación laboral colombiana (Ley 2466 de 2025)** e **integraciones contables ERP (EFFI)**— en plataformas de producción confiables.

• **Educación:** Estudiante de Ingeniería de Software en la **Institución Universitaria Pascual Bravo** (Medellín) y graduado del programa **Oracle Next Education (ONE)**.  
• **Sistemas en Producción:** Despliegue y administración de infraestructuras multi-tenant contenerizadas en **DigitalOcean VPS**, optimizadas con **Docker**, **Nginx Reverse Proxy**, **PostgreSQL** y **DigitalOcean Spaces (S3)**.  
• **Ingeniería de Calidad & Metodologías Ágiles:** Práctica constante de **Scrum**, especificación de requerimientos bajo estándar **INVEST**, criterios de aceptación en sintaxis **BDD / Gherkin**, protocolos de **Definition of Ready (DoR)** / **Definition of Done (DoD)**, Quality Gates y planes formales de remediación de QA.  
• **Cloud FinOps:** Liderazgo en migraciones estratégicas desde plataformas serverless de alto costo (Firebase) hacia arquitecturas propias contenerizadas, reduciendo los costos de operación en nube aproximadamente a la mitad.

---

## Proyectos y Casos de Estudio

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>NaTec & Zona Digital — E-Commerce B2B Multi-Tenant</h3>
      <p><b>Migración de Firebase a Backend Propio y Producción en DigitalOcean VPS</b></p>
      <ul>
        <li><b>Migración de Backend:</b> Lideré la migración completa desde Firebase (Firestore, Auth, Storage) hacia una API REST propia construida con <b>NestJS</b>, <b>PostgreSQL (Prisma ORM)</b> y autenticación JWT con bcrypt.</li>
        <li><b>Cero Downtime:</b> Migración de datos en vivo de Cloud Firestore a PostgreSQL y catálogos hacia <b>DigitalOcean Spaces (S3)</b> sin interrupción del servicio.</li>
        <li><b>Arquitectura Multi-Tenant & FinOps:</b> Despliegue Dockerizado que aloja múltiples aplicaciones de clientes independientes en un solo Droplet con Nginx reverse proxy, reduciendo los costos de nube a la mitad.</li>
        <li><b>Integración EFFI ERP:</b> Generador automatizado de plantillas Excel (.xlsx) para conceptos de venta y sincronización en tiempo real vía Server-Sent Events (SSE).</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Status-En_Producción-22c55e?style=flat-square"/>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>StockChef — ERP & POS Gastronómico Multi-Módulo</h3>
      <p><b>Ingeniería Formal con Scrum, Arquitectura Hexagonal y Puertas de Calidad</b></p>
      <ul>
        <li><b>Metodología Agile & Scrum Rigurosa:</b> Ciclo de vida estructurado con especificación de historias de usuario bajo estándar <b>INVEST</b> y criterios de aceptación formales en <b>BDD (Gherkin: Dado/Cuando/Entonces)</b>.</li>
        <li><b>Puertas de Calidad (IEEE 730 / ISO 29119):</b> Protocolo transversal de <b>Definition of Ready (DoR)</b> y <b>Definition of Done (DoD)</b>, Quality Gates con SonarQube (complejidad ciclomática &le; 10), cobertura de pruebas unitarias &ge; 85% (AAA) y planes de remediación de defectos (QA Remediation Plans).</li>
        <li><b>Arquitectura Hexagonal & DDD:</b> Bounded contexts delimitados, entidades de dominio, puertos/adaptadores en NestJS y PostgreSQL, con eventos en tiempo real vía <b>Redis Pub/Sub</b> y WebSockets para KDS (Kitchen Display System).</li>
        <li><b>Pruebas de Carga & Resiliencia:</b> Benchmarking de latencia con <b>k6</b> (500 comandas concurrentes, p95 &le; 200 ms) y tolerancia a fallos con sincronización offline-first.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Agile-Scrum-0284c7?style=flat-square&logo=jira&logoColor=white"/>
        <img src="https://img.shields.io/badge/QA-IEEE_730_%2F_ISO_29119-10b981?style=flat-square"/>
        <img src="https://img.shields.io/badge/Angular_Signals-DD0031?style=flat-square&logo=angular&logoColor=white"/>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Software de Turnos EDS — Cumplimiento Laboral Colombiano</h3>
      <p><b>Sistema de Escritorio para Liquidación de Turnos y Nómina (Electron)</b></p>
      <ul>
        <li><b>Motor de Liquidación Laboral:</b> Motor en JavaScript (<code>calculos.js</code>) aplicando límites de jornada legal (8h/día, 44 o 42h/semana), horas extras y recargos nocturnos del 35%.</li>
        <li><b>Reforma Laboral (Ley 2466 de 2025):</b> Automatización del recargo dominical y festivo dinámico según el periodo liquidado (80% inicial, 90% y 100%).</li>
        <li><b>Dashboard Ejecutivo Multi-Sede:</b> Panel gerencial que consolida indicadores de nómina (básicos, extras, recargos y neto a transferir) para hasta 15 estaciones de servicio.</li>
        <li><b>Distribución Desktop:</b> Empaquetado con Electron en instalador de Windows para operación 100% autónoma sin servidores externos.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white"/>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
        <img src="https://img.shields.io/badge/Ley_2466_de_2025-16a34a?style=flat-square"/>
        <img src="https://img.shields.io/badge/Multi--Sede-0ea5e9?style=flat-square"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Fuelix — Plataforma de Gestión Multi-Estación</h3>
      <p><b>Consolidación y Dashboard Ejecutivo para Estaciones de Servicio</b></p>
      <ul>
        <li><b>Dashboard Consolidado:</b> Panel ejecutivo multi-estación para supervisión centralizada de indicadores operativos y ventas.</li>
        <li><b>Diseño de Interfaz:</b> Componentes en Angular con Tailwind CSS y Atomic Design adaptados para una rápida navegación ejecutiva.</li>
        <li><b>Arquitectura Monorepo:</b> Configuración modular basada en npm workspaces dividida en frontend, backend y servicios comunes.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Angular_22-DD0031?style=flat-square&logo=angular&logoColor=white"/>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
        <img src="https://img.shields.io/badge/Monorepo-CB3837?style=flat-square&logo=npm&logoColor=white"/>
      </p>
    </td>
  </tr>
</table>

---

## Habilidades Técnicas & Stack

<div align="center">

### Lenguajes de Programación
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-CC292B?style=for-the-badge&logo=sqlite&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### Backend, APIs & Runtimes
![.NET Core](https://img.shields.io/badge/.NET_Core_%2F_9-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)

### Frontend & Arquitectura Web
![Angular](https://img.shields.io/badge/Angular_(Signals)-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![NextJS](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Bases de Datos & Modelado
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-black?style=for-the-badge)

### Cloud, DevOps & Metodologías de Calidad
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean_VPS_&_Spaces-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx_Reverse_Proxy-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Cloud FinOps](https://img.shields.io/badge/Cloud_FinOps-34D399?style=for-the-badge)
![Git](https://img.shields.io/badge/Git_%26_GitHub-F05032?style=for-the-badge&logo=git&logoColor=white)
![Scrum](https://img.shields.io/badge/Scrum_%2F_Agile-0284c7?style=for-the-badge&logo=scrumalliance&logoColor=white)
![QA Testing](https://img.shields.io/badge/QA_Testing_%2F_ISO_29119-10b981?style=for-the-badge&logo=testrail&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![k6](https://img.shields.io/badge/k6_Benchmarking-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

</div>

---

## Actividad en GitHub

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=PabloLinares06&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />
</div>

<div align="center" style="margin-top: 15px;">
  <img src="https://komarev.com/ghpvc/?username=PabloLinares06&color=0ea5e9&style=for-the-badge&label=Vistas+del+Perfil" alt="Vistas del Perfil" />
</div>

---

<div align="center">
  <p><i>Comprometido con la ingeniería de software de alto impacto, arquitecturas eficientes, metodologías ágiles y código limpio.</i></p>
  <p>Medellín, Colombia</p>
</div>