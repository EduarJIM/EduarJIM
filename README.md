<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,4&height=200&section=header&text=Eduar%20Jim%C3%A9nez%20L%C3%B3pez&fontSize=40&fontAlignY=38&animation=twinkling&desc=Full%20Stack%20Developer%20%C2%B7%20ADSO%20SENA&descAlignY=60&descAlign=50" width="100%" alt="Eduar Jiménez López — Full Stack Developer" />

  <img src="https://readme-typing-svg.demolab.com?lines=Full+Stack+Developer+%7C+ADSO+SENA;React+%E2%80%A2+TypeScript+%E2%80%A2+Python+%E2%80%A2+Node.js;Domain-Driven+Design+%26+Arquitectura+Limpia;Del+modelo+de+dominio+al+deploy&center=true&width=560&height=45&duration=3600&pause=900&color=38BDF8&font=Fira+Code&size=20" alt="Full Stack Developer | ADSO SENA" />

  <br>

  **Modelo el dominio antes de escribir la interfaz.**

  Aplicaciones web y de escritorio con reglas de negocio explícitas, arquitectura limpia y pruebas automatizadas.

  <br><br>

  <a href="https://github.com/EduarJIM"><img src="https://img.shields.io/badge/GitHub-EduarJIM-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/eduar-jim%C3%A9nez-0a96a3363/"><img src="https://img.shields.io/badge/LinkedIn-Eduar%20Jim%C3%A9nez-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:eworstef12@gmail.com"><img src="https://img.shields.io/badge/Email-eworstef12%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open%20to%20Work-34D399?style=for-the-badge&logo=github&logoColor=white" alt="Open to work" />

</div>

---

## 👤 Sobre mí

Tecnólogo en **Análisis y Desarrollo de Software (ADSO)** y **Full Stack Developer**. Construyo soluciones web y de escritorio con reglas de negocio explícitas, dominio aislado de la interfaz y pruebas automatizadas: del modelo al despliegue.

- **Enfoque:** reglas de negocio testeables antes que interfaces bonitas. DDD, Clean Architecture y SOLID aplicados de forma práctica.
- **Full stack:** interfaces en React + TypeScript; APIs y backends en Python (Django / Flask), Node.js y C# / .NET para escritorio.
- **Dominio explicable:** el mismo triaje veterinario en React y en WinForms, con documentación arquitectónica, diagramas Mermaid y 30 pruebas unitarias.
- **Buscando:** un equipo ágil donde aportar en producto y seguir creciendo como ingeniero.

## 🧰 Stack

| Área | Tecnologías |
| :-- | :-- |
| 🎨 Frontend | `React` `TypeScript` `JavaScript (ES6+)` `Tailwind CSS` `Bootstrap` `HTML5` `CSS3` `Vite` |
| ⚙️ Backend | `Python` `Django` `Flask` `Node.js` `C# / .NET 10` `WinForms` `APIs REST` |
| 🗄️ Datos | `PostgreSQL` `MySQL` `SQLite` `Supabase` `Modelado relacional` |
| 🧪 Ingeniería | `DDD` `Clean Architecture` `SOLID` `Pruebas unitarias (xUnit / Node test runner)` `GitHub Actions` `Git Flow` |
| 🛠️ Herramientas | `Git` `GitHub` `VS Code` `Visual Studio` `Figma` `Postman` `Docker` `Mermaid` `npm` |

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,js,python,django,flask,nodejs,html,css,tailwind,bootstrap,cs,supabase,mysql,postgres,sqlite,docker,git,github,githubactions,vite,npm,figma,vscode,postman&perline=12" alt="TypeScript, React, JavaScript, Python, Django, Flask, Node.js, HTML, CSS, Tailwind, Bootstrap, C#, Supabase, MySQL, PostgreSQL, SQLite, Docker, Git, GitHub, GitHub Actions, Vite, npm, Figma, VS Code, Postman" />
</p>

---

## 🚀 Proyectos destacados

### 🩺 Diagnostica tus Mascotas — Triaje en escritorio

Aplicación **standalone de Windows Forms + .NET 10** con el dominio de triaje veterinario llevado a escritorio: 20 síntomas, 3 niveles de urgencia, SQLite local y **30 pruebas xUnit**. Incluye documentación arquitectónica completa con 5 diagramas Mermaid.

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square)
![.NET 10](https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![WinForms](https://img.shields.io/badge/Windows_Forms-0078D6?style=flat-square&logo=windows&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit_30_tests-22C55E?style=flat-square)
![MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

<details>
<summary><b>Ver detalle técnico</b></summary>

- **Motor de triaje determinista y explicable:** pesos 1/2/3, regla especial *vómitos + diarrea* e implicaciones clínicas por síntoma.
- **Dominio desacoplado:** la capa `Core` no depende de la UI; la interfaz se dibuja con GDI+ y tiene tema claro/oscuro con animaciones propias.
- **Persistencia local:** mascotas, consultas, síntomas, recordatorios y preferencias en un único archivo SQLite en `%AppData%`.
- **Documentación como producto:** 5 diagramas Mermaid (contexto C4, clases, secuencia, estados y entidad-relación), ADR, guía de usuario, referencia de API y DDL.
- **Calidad:** 30 pruebas unitarias, CI que compila, ejecuta pruebas, recoge cobertura y audita dependencias.

</details>

**[→ Repositorio](https://github.com/EduarJIM/DiagnosticaTusMascotas)** · **[→ Documentación](https://github.com/EduarJIM/DiagnosticaTusMascotas/blob/main/docs/INDICE.md)**

### ⚡ Memphis — Agenda & Task Ops Management System

Consola táctica de agenda con **4 portales independientes**, motor de dominio inmutable y 5 reglas de negocio validadas en vivo.

![TypeScript](https://img.shields.io/badge/TypeScript_5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![DDD](https://img.shields.io/badge/Domain--Driven_Design-BA0659?style=flat-square)
![Tests](https://img.shields.io/badge/16_unit_tests-22C55E?style=flat-square)

<details>
<summary><b>Ver detalle técnico</b></summary>

- **4 portales aislados:** Panel general (métricas en vivo), Gestor de tareas, Calendario cronológico y Laboratorio de reglas con simulador de colisiones.
- **Reglas de dominio:** prioridad tipada y vencimiento futuro (RN-01), estados terminales irreversibles (RN-02), *Zero-Overlap* con citas contiguas permitidas (RN-03), duración mínima de 15 min (RN-04) y validación RFC 5322 de participantes (RN-05).
- **Modelo en TypeScript** (entidades, Value Objects, DTOs) y motor de dominio en JavaScript ES6+ con estructuras inmutables.
- **16 pruebas unitarias** ejecutables desde la propia interfaz, sin depender de la UI.
- Persistencia en `localStorage` y servidor estático con el módulo HTTP nativo de Node.

</details>

**[→ Repositorio](https://github.com/EduarJIM/Memphis-agenda-management-system)**

### 🚦 MoviliData OS — Movilidad Urbana Inteligente

Plataforma que analiza tráfico, clima e incidentes viales, y **predice congestión con Machine Learning**.

![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django_5-092E20?style=flat-square&logo=django&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![ML](https://img.shields.io/badge/Random_Forest-FF6F00?style=flat-square)

<details>
<summary><b>Ver detalle técnico</b></summary>

- Dashboard con estado del tráfico, indicadores de congestión, alertas activas y estadísticas urbanas.
- Mapas interactivos con marcadores dinámicos, heatmaps de siniestralidad y cálculo de rutas óptimas.
- Modelo predictivo (Random Forest) para estimar congestión futura y riesgo vial a partir de datos históricos.
- Motor de alertas automáticas por accidentes, congestión severa y eventos climáticos.
- Reportes históricos con tendencias semanales y comparativas mensuales.

</details>

**[→ Repositorio](https://github.com/EduarJIM/MoviliData)**

### 📋 api-edi — API REST & Panel de Tareas

API REST y panel web para gestión de tareas, **contenerizada con Docker y desplegada en Render**.

![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask_3-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

<details>
<summary><b>Ver detalle técnico</b></summary>

- CRUD de tareas con estados (`pendiente`, `en_progreso`, `suspendido`, `completado`), prioridades y validación de esquema.
- Endpoint `/api/health` para monitoreo del servicio.
- Colección de Postman con los 8 pasos de evidencia de la API.
- Despliegue público en Render con PostgreSQL administrado. *Si estaba inactivo, el primer request tarda ~50 s (cold start del plan gratuito).*

</details>

**[→ Repositorio](https://github.com/EduarJIM/api-edi)** · **[→ Demo en vivo](https://api-edi-iqx3.onrender.com)**

---

## 📂 Otros repositorios

- **[spa-canino-kuky-pets](https://github.com/EduarJIM/spa-canino-kuky-pets)** — Gestión de spa canino: CRUD, agendamiento, historiales y reportes. *Colaboración sobre un fork de [@michelbarros178-dot](https://github.com/michelbarros178-dot).* · `React` `Supabase`

---

## 🧭 Cómo trabajo

1. **Especifico antes de programar.** Las reglas de negocio se escriben como casos verificables (RN-01…RN-05 en Memphis), no se descubren a mitad del código.
2. **El dominio no depende de la UI.** Modelos y validaciones viven en su propia capa, por eso se pueden probar sin abrir la interfaz.
3. **Cierro con pruebas.** Cada funcionalidad termina con pruebas unitarias y un flujo de Git con ramas y commits descriptivos.

---

## 📫 Contacto

Estoy disponible para **posiciones de desarrollo junior/trainee, prácticas y proyectos freelance**.

📧 [eworstef12@gmail.com](mailto:eworstef12@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/eduar-jim%C3%A9nez-0a96a3363/) · 🐙 [GitHub](https://github.com/EduarJIM)

<div align="center">
  <br>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,4&height=110&section=footer" width="100%" alt="" />
  <sub><i>"La simplicidad es el requisito previo para la confiabilidad."</i> — Edsger W. Dijkstra</sub>
</div>
