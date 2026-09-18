<div align="center">

# Juan Pablo Linares Laverde
### Software Engineer | Full-Stack & Cloud Architecture

<p align="center">
  <a href="https://github.com/PabloLinares06">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=2800&pause=1200&color=38BDF8&center=true&vCenter=true&width=620&lines=Software+Engineer+%7C+Full-Stack+Developer;.NET+Core+%7C+Angular+%7C+NestJS+%7C+PostgreSQL;Cloud+FinOps+%7C+Multi-Tenant+Architectures;ERP+Integrations+%7C+Colombian+Labor+Compliance" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/jplinaresdev"><img src="https://img.shields.io/badge/LinkedIn-jplinaresdev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:juanpalinare@gmail.com"><img src="https://img.shields.io/badge/Email-juanpalinare%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Ubicaci%C3%B3n-Medell%C3%ADn%2C%20Colombia-0ea5e9?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Medellín, Colombia" />
</p>

---

</div>

## 📌 Sobre Mí

Desarrollador de Software con experiencia práctica construyendo aplicaciones modernas, escalables y eficientes tanto en **entornos empresariales (.NET / C#)** como en **soluciones full-stack en la nube (Angular, NestJS, PostgreSQL)**.

Especializado en el diseño de **APIs REST robustas**, **migración y arquitectura de backend**, **optimización de costos en la nube (Cloud FinOps)**, y en traducir requerimientos de negocio y normativos complejos —incluyendo **lógica de nómina bajo la legislación laboral colombiana (Ley 2466 de 2025)** e **integraciones contables ERP (EFFI)**— en sistemas de producción confiables.

* 🎓 **Educación:** Estudiante de Ingeniería de Software en la **Institución Universitaria Pascual Bravo** (Medellín) y graduado del programa **Oracle Next Education (ONE)**.
* 🚀 **Sistemas en Producción:** Administro y despliego infraestructuras Dockerizadas multi-tenant sobre VPS en **DigitalOcean** con **Nginx**, **PostgreSQL** y **Spaces (S3)**.
* 💡 **Cloud FinOps:** Experiencia liderando migraciones desde plataformas serverless costosas (Firebase) hacia arquitecturas propias autoalojadas, reduciendo costos de infraestructura aproximadamente a la mitad.

---

## 🚀 Proyectos y Experiencia en Producción

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ NaTec & Zona Digital — E-Commerce B2B Multi-Tenant</h3>
      <p><b>Migración de Firebase a Backend Propio y Producción en DigitalOcean VPS</b></p>
      <ul>
        <li><b>Migración de Backend:</b> Lideré la migración completa desde Firebase (Firestore, Auth, Storage) hacia una API REST propia construida con <b>NestJS</b>, <b>PostgreSQL (Prisma ORM)</b> y autenticación JWT con bcrypt.</li>
        <li><b>Cero Downtime:</b> Migración de datos en vivo de Cloud Firestore a PostgreSQL y catálogos hacia <b>DigitalOcean Spaces (S3)</b> sin interrupción del servicio.</li>
        <li><b>Arquitectura Multi-Tenant & FinOps:</b> Despliegue Dockerizado que aloja múltiples aplicaciones de clientes independientes en un solo Droplet con Nginx reverse proxy, reduciendo los costos de nube a la mitad.</li>
        <li><b>Integración EFFI ERP:</b> Generador automatizado de plantillas Excel (.xlsx) para conceptos de venta y sincronización en tiempo real vía Server-Sent Events (SSE).</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Status-En_Producci%C3%B3n-22c55e?style=flat-square"/>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⏰ Software de Turnos EDS — Cumplimiento Laboral Colombiano</h3>
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
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🍳 StockChef — ERP & POS para Cadenas Gastronómicas</h3>
      <p><b>Plataforma Modular de Gestión de Restaurantes y Comandas</b></p>
      <ul>
        <li><b>Arquitectura Limpia:</b> Backend modular en NestJS con PostgreSQL y frontend reactivo en Angular con Signals.</li>
        <li><b>Concurrencia & Tiempo Real:</b> Sincronización de pedidos y cocina mediante Redis Pub/Sub para comunicación de baja latencia.</li>
        <li><b>Control de Costos & Escandallo:</b> Deducción de insumos por receta y comparativa de Food Cost teórico vs. real.</li>
        <li><b>Pruebas de Carga:</b> Verificación de rendimiento y confiabilidad con suites de Jest y k6.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Angular_Signals-DD0031?style=flat-square&logo=angular&logoColor=white"/>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⛽ Fuelix — Plataforma de Gestión Multi-Estación</h3>
      <p><b>Consolidación y Dashboard Ejecutivo para Estaciones de Servicio</b></p>
      <ul>
        <li><b>Dashboard Consolidado:</b> Panel ejecutivo multi-estación para supervisión centralizada de indicadores de venta y turnos.</li>
        <li><b>Diseño de Interfaz:</b> Componentes en Angular con Tailwind CSS y Atomic Design adaptados para rápida operación.</li>
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

## 🛠️ Habilidades Técnicas

<div align="center">

### 💻 Lenguajes
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-CC292B?style=for-the-badge&logo=sqlite&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### ⚙️ Backend & Runtimes
![.NET Core](https://img.shields.io/badge/.NET_Core_%2F_9-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)

### 🎨 Frontend & UI
![Angular](https://img.shields.io/badge/Angular_(Signals)-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![NextJS](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### 🗄️ Bases de Datos & ORMs
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-black?style=for-the-badge)

### ☁️ Cloud, Infraestructura & DevOps
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean_VPS_&_Spaces-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx_Reverse_Proxy-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Cloud FinOps](https://img.shields.io/badge/Cloud_FinOps-34D399?style=for-the-badge)
![Git](https://img.shields.io/badge/Git_%26_GitHub-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📊 Actividad en GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PabloLinares06&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&bg_color=0d1117" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=PabloLinares06&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />
</div>

---

<div align="center">
  <p><i>Comprometido con la ingeniería de software de alto impacto, arquitecturas eficientes y código limpio.</i></p>
  <p>📍 Medellín, Colombia</p>
</div>
