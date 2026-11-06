# ⚙️ Automation & Systems Integration

<p align="center">
  <a href="https://github.com/miguelnavarrosc/miguelnavarrosc/blob/main/README.md">🏠 Home</a> &nbsp;|&nbsp;
  <a href="https://github.com/miguelnavarrosc/miguelnavarrosc/blob/main/automation.md"><b>⚙️ Automation</b></a> &nbsp;|&nbsp;
  <a href="https://github.com/miguelnavarrosc/miguelnavarrosc/blob/main/fullstack.md">🏛️ Full Stack & Arch</a> &nbsp;|&nbsp;
  <a href="https://github.com/miguelnavarrosc/miguelnavarrosc/blob/main/ai.md">🧠 AI & Machine Learning</a> &nbsp;|&nbsp;
  <a href="https://github.com/miguelnavarrosc/miguelnavarrosc/blob/main/research.md">🔬 Research & Frontier Lab</a>
</p>

---

### 🎯 Overview & Value Proposition

Especializado en **automatización de procesos empresariales**, **integración e interoperabilidad de APIs corporativas** y **soluciones RPA**. 

Diseño sistemas desatendidos que conectan plataformas líderes del mercado (**Microsoft 365, Oracle CX Sales, Oracle Eloqua, Meta Ads, Canvas LMS**) para eliminar fricción operativa, asegurar la trazabilidad de datos críticos y optimizar costos de infraestructura.

---

### 🏆 Proyectos Destacados de Automatización

A continuación, los proyectos y arquitecturas de integración desarrollados:

---

#### 1. 🔄 Omnichannel Lead Synchronization & Tracking Pipeline (Meta ➔ Oracle Eloqua & CX Sales)
* **El Problema:** Pérdida de trazabilidad y retrasos en el traspaso de prospectos comerciales generados en campañas de pauta digital hacia las plataformas corporativas de marketing y ventas.
* **La Solución:** Pipeline híbrido de **RPA y consumo de APIs** que captura leads en tiempo real desde **Meta Lead Ads**, valida y enriquece la información, y la sincroniza bidireccionalmente entre **Oracle Eloqua (Marketing Automation)** y **Oracle CX Sales (CRM)**.
* **Aspectos Técnicos:**
  * Manejo seguro de tokens OAuth2 y autenticación corporativa.
  * Resiliencia ante fallos de red con reintentos exponenciales (*exponential backoff*).
  * Automatización RPA para conciliación de registros en interfaces donde la API tiene restricciones.
* **Stack:** `Python`, `Meta Graph API`, `Oracle Eloqua REST API`, `Oracle CX Sales API`, `Selenium / RPA`, `JSON`, `Webhooks`.

---

#### 2. ☁️ M365 SharePoint Storage Optimizer & Version Lifecycle Cleaner
* **El Problema:** Acumulación desmedida de versiones históricas en bibliotecas de SharePoint Online, provocando sobrecostos por consumo de almacenamiento adicional en Microsoft 365.
* **La Solución:** Script de automatización que audita dinámicamente las bibliotecas de documentos en **SharePoint M365**, evalúa las políticas de retención y ejecuta la purga controlada de versiones obsoletas a través de llamadas autenticadas a **Microsoft Graph API**.
* **Aspectos Técnicos:**
  * Autenticación basada en aplicación (Azure AD / Microsoft Entra ID App Registration).
  * Paginación eficiente para millones de registros de metadatos de archivos.
  * Logging de auditoría detallado para garantizar conformidad y control de cambios.
* **Stack:** `Python`, `Microsoft Graph API`, `SharePoint REST API`, `Azure AD / Entra ID`, `OAuth2`.

---

#### 3. 🎓 Canvas LMS Notification Engine & Academic Monitoring System
* **El Problema:** Necesidad de supervisar de forma proactiva eventos académicos (entregas de tareas, inactividad, calificaciones) y emitir alertas inmediatas sin requerir supervisión manual de los administradores.
* **La Solución:** Motor de automatización que consulta periódicamente los endpoints de **Canvas LMS REST API**, analiza el estado de actividad de los cursos, persiste el historial en una base de datos relacional **MySQL** y dispara notificaciones automáticas y alertas según reglas de negocio.
* **Aspectos Técnicos:**
  * Modelado relacional en MySQL para tracking de cambios de estado y control de notificaciones duplicadas.
  * Manejo de *Rate Limits* y paginación mediante cabeceras HTTP de Canvas API.
  * Despacho automático de alertas por correo y mensajería.
* **Stack:** `Python`, `Canvas LMS REST API`, `MySQL`, `SQLAlchemy / PyMySQL`, `Task Scheduler / Cron`.

---

### 🛠️ Automation & Integration Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,mysql,postgres,docker,git,github,linux,bash&perline=8" alt="Automation Stack" />
</div>

<br/>

| Dimensión | Tecnologías & Ecosistemas |
| :--- | :--- |
| **Integraciones Enterprise** | Microsoft Graph API (M365, SharePoint), Oracle Eloqua, Oracle CX Sales, Meta Graph API, Canvas LMS |
| **Lenguajes & Automatización** | Python (Requests, HTTPX, Aiohttp, Selenium, Playwright, BeautifulSoup) |
| **Persistencia & Datos** | MySQL, PostgreSQL, Relational Data Modeling, SQL Query Optimization, JSON/CSV ETL |
| **Seguridad & Protocolos** | OAuth 2.0, Microsoft Entra ID (Azure AD), Bearer Tokens, Webhooks, RESTful APIs |
| **Despliegue & Orquestación** | Docker, Cron, Windows Task Scheduler, Linux Daemons, GitHub Actions |

---

### 📂 Matriz de Proyectos

| Proyecto | Plataformas Conectadas | Tipo de Solución | Repositorio / Estado |
| :--- | :--- | :--- | :--- |
| **Lead Tracking Pipeline** | Meta Ads ➔ Oracle Eloqua ➔ Oracle CX Sales | RPA + API Integration | *Showcase / Implementado* |
| **SharePoint Cleaner** | Microsoft 365, SharePoint Online | Cloud Governance & Graph API | *Showcase / Implementado* |
| **Canvas LMS Monitor** | Canvas LMS ➔ Base de Datos MySQL | Event Monitoring & Notifications | *Showcase / Implementado* |

---

<div align="center">
  <a href="https://github.com/miguelnavarrosc/miguelnavarrosc/blob/main/README.md">← Volver al Perfil Principal</a>
</div>
