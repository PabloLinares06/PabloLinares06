<div align="center">

# Juan Pablo Linares Laverde
### Software Engineer & Systems Architect

<p align="center">
  <a href="https://github.com/PabloLinares06">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1200&color=38BDF8&center=true&vCenter=true&width=620&lines=Software+Engineer+%7C+Systems+Architect;Offline-First+%26+Distributed+Systems;Edge+IoT+%7C+Multi-Tenant+Cloud+SaaS;High-Concurrency+Backends+%26+Modern+Web" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="mailto:juanpablolinares06@gmail.com"><img src="https://img.shields.io/badge/Email-Contactar-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/PabloLinares06"><img src="https://img.shields.io/badge/GitHub-PabloLinares06-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://img.shields.io/badge/Location-Medell%C3%ADn%2C%20Colombia-0ea5e9?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
</p>

---

</div>

## 📌 Sobre Mí

Soy **Ingeniero de Software y Arquitecto de Sistemas**, enfocado en la concepción y desarrollo de **sistemas de misión crítica, arquitecturas offline-first y plataformas distribuidas**. Me especializo en conectar hardware/edge computing (Raspberry Pi, dispositivos seriales, balanzas y dispensadores) con backends cloud multi-tenant escalables y clientes táctiles (Angular Signals / Next.js) construidos para operar bajo condiciones ambientales y de red extremas.

* 🌐 **Sistemas en Producción:** Arquitecto y mantenedor de stacks en producción real sobre VPS DigitalOcean con Docker Compose, Nginx y PostgreSQL.
* ⚡ **Arquitectura:** Diseños desacoplados *Offline-First* con spools locales, sincronización bidireccional idempotente y topologías híbridas Edge-to-Cloud.
* 📋 **Cumplimiento Regulatorio & Fiscal:** Implementación de facturación electrónica DIAN (Resolución 000042), metrología legal SIC (Resolución 77507/2016) e integraciones contables ERP (EFFI).

---

## 🚀 Proyectos y Sistemas Destacados

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⛽ Fuelix — Offline-First Gas Station IoT & Cloud SaaS</h3>
      <p>Plataforma integral de control de pista, POS e inventarios para Estaciones de Servicio (EDS) en Colombia y Latinoamérica. Sustituye costosos controladores propietarios por nodos de borde commodity (~$50 Raspberry Pi + Servidor Local).</p>
      <ul>
        <li><b>Edge Gateway:</b> Monitoreo serial pasivo RS-232/RS-485 con cola local SQLite garantizando venta continua ante caídas de red y apagado del PC.</li>
        <li><b>Límite Legal SIC:</b> Estricta separación de metrología legal (SIC Res. 77507/2016).</li>
        <li><b>UX de Isla:</b> Angular 22 PWA con visibilidad outdoor bajo luz solar directa, reconciliación de turnos y reporte SICOM.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Angular_22-DD0031?style=flat-square&logo=angular&logoColor=white"/>
        <img src="https://img.shields.io/badge/NestJS_11-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
        <img src="https://img.shields.io/badge/Offline--First-0ea5e9?style=flat-square"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🍳 StockChef — Event-Driven ERP & POS for Restaurant Chains</h3>
      <p>ERP y sistema de comandeo para alta gastronomía con arquitectura híbrida Edge/Cloud y sincronización en tiempo real sub-500ms entre salones y pantallas KDS.</p>
      <ul>
        <li><b>Hub Local Resiliente:</b> Servidor local PC con PostgreSQL + Redis Pub/Sub que mantiene operativo el restaurante al 100% sin internet.</li>
        <li><b>Escandallo Atómico:</b> Explosión de recetas al gramo al despachar platillos; comparación Food Cost Teórico vs. Real y trazabilidad INVIMA.</li>
        <li><b>Fiscal DIAN:</b> Validación transaccional de rangos consecutivos y CUFE (Res. 000042) y arqueos ciegos X/Z.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Angular_Signals-DD0031?style=flat-square&logo=angular&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis_Pub%2FSub-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/DIAN_000042-16a34a?style=flat-square"/>
        <img src="https://img.shields.io/badge/k6_Testing-7D64FF?style=flat-square&logo=k6&logoColor=white"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ NaTec — Wholesale Commerce & EFFI Accounting ERP</h3>
      <p>Plataforma comercial y catálogo mayorista desplegada en producción real sobre DigitalOcean VPS con integración ERP contable nativa.</p>
      <ul>
        <li><b>Integración EFFI ERP:</b> Generador automatizado de plantillas Excel (.xlsx) para conceptos de venta y pipeline de pedidos SSE en tiempo real.</li>
        <li><b>Modo Kiosko Físico:</b> Interfaz táctil interactiva para tienda presencial con bloqueo por PIN y reinicio automático por inactividad.</li>
        <li><b>Motor Canvas 2D HD:</b> Composición visual limpia de fichas publicitarias oficiales con pegado directo en WhatsApp Web (Ctrl+V).</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Status-Live_in_Production-22c55e?style=flat-square"/>
        <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white"/>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
        <img src="https://img.shields.io/badge/EFFI_ERP-0284c7?style=flat-square"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📱 Zona Digital — High-Traffic Store & S3 CDN</h3>
      <p>Catálogo digital y plataforma comercial optimizada en producción real con microstack Dockerizado y entrega ultrarrápida de media.</p>
      <ul>
        <li><b>Cloud Object Storage:</b> Integración con DigitalOcean Spaces (S3 CDN) para streaming y carga multimedia instantánea.</li>
        <li><b>Aislamiento en VPS:</b> Stack multi-tenant con contenedor web Nginx y API NestJS completamente aislados.</li>
        <li><b>Kiosko & Exportador:</b> Adaptación personalizada de interfaces táctiles y motor gráfico para revendedores en WhatsApp.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Status-Live_in_Production-22c55e?style=flat-square"/>
        <img src="https://img.shields.io/badge/DigitalOcean_Spaces-0080FF?style=flat-square&logo=digitalocean&logoColor=white"/>
        <img src="https://img.shields.io/badge/Nginx_SPA-009639?style=flat-square&logo=nginx&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Stack Tecnológico y Dominio de Herramientas

<div align="center">

### 💻 Lenguajes & Core
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC292B?style=for-the-badge&logo=sqlite&logoColor=white)

### ⚙️ Backend, Edge & Protocolos
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_Pub/Sub-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=for-the-badge&logo=typeorm&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_IoT-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)

### 🎨 Frontend & UI/UX
![Angular](https://img.shields.io/badge/Angular_22_(Signals)-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![NextJS](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

### ☁️ Infraestructura, Cloud & DevOps
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean_VPS_&_Spaces-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx_Reverse_Proxy-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Ubuntu_Debian-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 🧪 Testing & Calidad
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![k6](https://img.shields.io/badge/k6_Load_Testing-7D64FF?style=for-the-badge&logo=k6&logoColor=white)

</div>

---

## 📊 Estadísticas de GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PabloLinares06&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&bg_color=0d1117" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=PabloLinares06&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PabloLinares06&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top Languages" />
</div>

---

<div align="center">
  <p><i>"Tu estación, bajo tu control. Tu restaurante, bajo tu control."</i></p>
  <p>Diseñado con pasión por la arquitectura robusta y la ingeniería de software de alto impacto.</p>
</div>
