# Hola, soy Andrea 👋

<div align="center">

**Full Stack Developer | Producto, automatización e IA aplicada**

*15 años construyendo sistemas que corren solos en producción*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andrea--tassi--it-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrea-tassi-it)
[![Portfolio](https://img.shields.io/badge/Portfolio-actassi.vercel.app-00C7B7?style=for-the-badge&logo=vercel&logoColor=white)](https://cv-actassi.vercel.app)
[![Email](https://img.shields.io/badge/Contacto-LinkedIn-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](https://linkedin.com/in/andrea-tassi-it)

</div>

---

## 🚀 Sobre mí

Full Stack Developer con 15 años construyendo sistemas empresariales desde cero, hoy enfocada en SaaS con IA integrada y automatización de procesos reales de negocio.

```javascript
const andrea = {
  ubicacion: "Funes, Santa Fe, Argentina",
  especialidad: ["React", "Node.js", "TypeScript", "Python", "Automatización con agentes de IA"],
  añosProgramando: 15,
  buscando: "Proyectos de desarrollo web y automatización (remoto/híbrido)",

  shippeandoAhora: {
    saasPropio: "ObraPlanner — SaaS de gestión de obras en producción, con asistente de IA incluido en el plan",
    proyectoPropio: "QRSafe — verificación de QR de pago vía bot de WhatsApp",
    automatizaciones: [
      "Cotejo fiscal automático (ARCA vs. contable)",
      "Recibos de sueldo digitales + libro de sueldos",
      "Integraciones Tienda Nube ↔ sistemas de gestión",
    ],
  },

  superpoder: "Convertir procesos manuales de negocio en sistemas que corren solos",

  curiosidad: "Empecé automatizando con VBA en 2011. Sigo automatizando — solo que ahora un agente de IA escribe parte del código conmigo 🔥",
};
```

### 💡 Lo que aporto

- ✅ **15 años** construyendo software que corre en producción real, sin red de contención
- ✅ **SaaS propio en producción** (ObraPlanner) con empresas pagando por el producto
- ✅ **Mentalidad full-stack real** — diseño de datos, backend, frontend y el proceso de negocio detrás
- ✅ **Automatización con impacto medible** — llevé procesos fiscales y de nómina de horas a minutos
- ✅ **IA como parte del flujo de trabajo**, no como demo: agentes integrados en producción y en mis propias herramientas internas
- ✅ **Debugging y mantenimiento** — 15 años sosteniendo sistemas críticos sin fallas

---

## 🛠️ Stack Tecnológico

### 💻 Actualmente trabajando con

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

### 🗄️ Bases de Datos & Backend

<div align="center">

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Microsoft Access](https://img.shields.io/badge/Access-A4373A?style=for-the-badge&logo=microsoft-access&logoColor=white)

</div>

### 🤖 IA & Automatización

<div align="center">

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=openai&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-217346?style=for-the-badge&logo=microsoft&logoColor=white)

</div>

---

## 🔥 Proyectos Destacados

### 🏗️ ObraPlanner — SaaS para la Industria de la Construcción

**Plataforma SaaS multi-tenant en producción, con empresas reales pagando**

```
Stack: React 18 · TypeScript · Tailwind CSS 4 · Node.js · Hono · Prisma · PostgreSQL
Infra:  Turborepo (monorepo) · Vercel (frontend) · Render (API) · Neon (DB)
```

Producto que diseñé y construí desde cero para digitalizar la planificación diaria de obras en Argentina: asignación de personal, vehículos y tareas en un canvas drag-and-drop, con generación automática de la programación del día y envío por WhatsApp en un clic.

**Highlights:**
- 🎨 Canvas interactivo con `@xyflow/react` + `@dnd-kit`: obras, subtareas, movilidades y personal
- 🤖 Asistente de IA incluido en el plan, con guardrails de alcance propios
- 💳 Alta self-serve con verificación de email y suscripciones vía MercadoPago (alta, baja y reconciliación automática)
- 🔐 Autenticación multi-tenant con `better-auth` · roles: admin, encargado, auditor, gerencia
- 🗺️ Módulo Gantt con clima por obra, historial, stock de materiales y partes diarios
- 💾 Backups automáticos diarios vía GitHub Actions

[🌐 Ver App en Producción](https://obraplanner.com.ar)

---

### 🔐 QRSafe — Verificación de QR de pago por WhatsApp

**Proyecto propio, repo público**

```
Stack: React + Vite · Express · TypeScript · Supabase (PostgreSQL) · Kapso (WhatsApp API)
```

Verificación de QR de pago basada en la relación entre un comercio y los códigos que declara como propios — no en la apariencia del QR. El comercio registra sus puntos de cobro; cualquier persona consulta un código por WhatsApp antes de pagar y recibe evidencia positiva, falta de cobertura, anomalías estructurales o código ilegible, nunca un veredicto inventado.

**Highlights:**
- 🔎 Motor de verificación propio (`@qrsafe/verification`): huella SHA-256 del payload decodificado
- 🤖 Bot de WhatsApp vía Kapso, con validación de firma HMAC-SHA256 en cada webhook
- 🖥️ Panel del comercio en React + Vite para altas de empresa, puntos de cobro y bindings de QR

[💻 Ver repo en GitHub](https://github.com/actassi/QRSafe)

---

### ⚙️ Automatización de procesos reales de negocio

Proyectos de automatización que desarrollé para una empresa real (RSR Ingeniería) y para comercios que uso como Partner de plataformas de e-commerce. Por confidencialidad de datos de clientes y empleados, estos no tienen repo público, pero sí producción real y uso diario:

- **Cotejo fiscal automático** — cruza los comprobantes de ARCA contra la base contable, detecta faltantes, excedentes y discrepancias de importes (Python + Access/SQL)
- **Recibos de sueldo digitales** — genera los recibos (Decreto 407/26) y el libro de sueldos automáticamente, corriendo 100% local para proteger datos de empleados (Python + SQLite)
- **Automatización de facturas** — skill de agente que matchea facturas de proveedores contra el contable, las renombra, carga y dispara la impresión (PowerShell + agente de IA)
- **Integraciones Tienda Nube ↔ gestión** — como Partner de Tienda Nube, integración OAuth2 con su API y sincronización bidireccional de catálogo (por SKU, con imágenes y variantes) hacia sistemas de gestión como LaPyme

---

### 💼 Antecedentes: sistemas empresariales en producción desde 2011

#### Sistema de Gestión Financiera
```javascript
const proyecto = {
  stack: ["VBA", "SQL", "Microsoft Access", "Outlook API"],
  tipo: "Aplicación Full Stack Empresarial",
  impacto: "Reducción de tiempo de 6 horas → 5 minutos (99%)",
  escala: "Procesando miles de transacciones durante 15 años",
  features: [
    "Procesamiento automático de facturas",
    "Generación de órdenes de pago",
    "Integración con sistema fiscal",
    "Automatización de emails",
    "Validación anti-duplicados",
  ],
};
```

#### Sistema de Nómina Escalable
```javascript
const proyecto = {
  stack: ["Microsoft Access", "VBA", "SQL", "Power Pivot"],
  tipo: "Aplicación Full Stack de RRHH",
  impacto: "Reducción mensual de 8 horas → 10 minutos",
  escalabilidad: "Creció de 5 a 30 empleados sin refactoring",
  features: [
    "Diseño de base de datos relacional",
    "Lógica de negocio para cálculos complejos",
    "UI personalizada para carga de datos",
    "Reportes dinámicos para gerencia",
  ],
};
```

Estos sistemas siguen en producción, y son la base sobre la que después construí las automatizaciones en Python que uso hoy para los mismos procesos.

---

## 🌱 Actualmente profundizando

```javascript
const aprendizaje = {
  actual: [
    "Agentes de IA para desarrollo (arquitectura, roles y flujos)",
    "Claude Code, Codex y OpenCode para entrega end-to-end",
    "Skills, MCP, memoria/contexto y estrategias de prompting",
    "Uso de IDEs + terminal con automatización asistida",
  ],
  proximo: [
    "Flujos multiagente con validación automática",
    "Testing-first para agentes autónomos",
    "Orquestación de pipelines de desarrollo con IA",
  ],
  objetivo: "Combinar 15 años de experiencia en desarrollo con IA aplicada para acelerar calidad, foco y entrega",
};
```

---

## 💼 Qué estoy buscando

Estoy abierta a proyectos y roles donde pueda aportar:

- 🚀 15 años de experiencia resolviendo problemas reales de negocio con código
- 💻 Desarrollo full-stack con React, Node.js, TypeScript y Python
- 🤖 Automatización de procesos con agentes de IA integrados al flujo de trabajo
- 🗄️ Diseño de datos y arquitectura de sistemas, no solo interfaz
- 🌍 Modalidad remota o híbrida (basada en Argentina)

### 🎯 Roles ideales

- Full Stack Developer (React / Node.js)
- Desarrolladora de producto para SaaS
- Automatización de procesos con IA / Agentes

---

## 📫 ¡Conectemos!

Siempre abierta a conversar sobre:

- 💼 Oportunidades laborales
- 🤝 Colaboración en proyectos
- 💡 Discusiones técnicas
- 🌱 Automatización e IA aplicada

**Contactame:**

- 💼 [LinkedIn](https://linkedin.com/in/andrea-tassi-it)
- 🌐 [Portfolio](https://cv-actassi.vercel.app)
- 📍 Funes, Santa Fe, Argentina

---

## 🏆 Logros

```javascript
const logros = {
  produccion: {
    añosEnProduccion: 15,
    sistemasDesarrollados: "Múltiples aplicaciones full-stack",
    reduccionDeTiempo: "99% (de horas a minutos) en procesos fiscales y de nómina",
    escalabilidad: "Crecimiento 500% sin refactoring",
    uptime: "15 años sin fallas críticas",
  },

  proyectosRecientes: {
    saasPropio: "ObraPlanner — SaaS en producción con empresas reales y asistente de IA",
    proyectoPublico: "QRSafe — bot de verificación de QR de pago vía WhatsApp",
    automatizaciones: "Cotejo fiscal, sueldos digitales, integraciones Tienda Nube ↔ gestión",
  },

  diferencial: {
    fortaleza: "Resolución de problemas nivel senior aplicada a herramientas y stacks modernos",
    mentalidad: "Código production-ready, siempre",
    enfoque: "Automatizar lo repetitivo, medir el impacto",
  },
};
```

---

## 💭 Mi filosofía de código

> **"El mejor código no es el más complejo - es el que resuelve el problema del negocio elegantemente y puede ser mantenido años después."**

Después de 15 años manteniendo mi propio código, aprendí:

- ✨ El diseño simple y robusto supera al código complejo y frágil
- ✨ Entender el problema de negocio es tan importante como escribir código
- ✨ La escalabilidad debe planificarse desde el día 1
- ✨ El código debe ser mantenible por años, no solo meses
- ✨ Los buenos nombres son mejores que los comentarios
- ✨ Production-ready significa pensar en casos edge

---

<div align="center">

### 💫 15 años construyendo sistemas, hoy con IA como parte del proceso

### 🚀 Lista para aportar experiencia real a tu producto o a tu proceso de negocio

**¡Gracias por visitar!** ⭐

</div>

---

## 📈 Actividad

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->
