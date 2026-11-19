# NexusFlow — Landing Page (Alternativa Open-Source estilo n8n)

Landing page moderna, responsiva e interactiva para una aplicación de automatización de flujos de trabajo y agentes de IA inspirada en **n8n**, **Zapier** y **Make**.

---

## 🚀 Características incluidas en la Landing

1. **Hero Section de Alto Impacto:**
   - Titular llamativo y propuesta de valor enfocada en desarrolladores.
   - Botón para copiar el comando de inicio rápido con **Docker** en un solo clic.
   - Enlace y métricas de GitHub (stars).

2. **Simulador de Flujo de Trabajo Interactivo (Estilo Editor de n8n):**
   - Lienzo visual con cuadrícula (*grid pattern*) y nodos conectados mediante cables SVG animados.
   - **Nodos representados:**
     - `Trigger`: Webhook de Stripe.
     - `Agente IA`: Clasificador de Leads con Gemini 1.5 Pro.
     - `Router/Switch`: Bifurcación condicional según calificación del lead.
     - `Outputs`: Alerta en canal de Slack VIP y persistencia en base de datos PostgreSQL.
   - **Botón "Ejecutar Flujo":** Simula en tiempo real la animación de datos viajando nodo por nodo con indicadores de estado e inspección JSON interactiva al pulsar cualquier nodo.

3. **Propuesta de Valor & Diferenciadores:**
   - 100% Autohospedable (*Self-Hosted*) para privacidad total y cumplimiento GDPR/HIPAA.
   - Nodos nativos de Agentes Autónomos con memoria vectorial (RAG) y LLMs.
   - Soporte para ejecutar JavaScript y Python nativo dentro de cualquier paso.

4. **Ecosistema de Integraciones:**
   - Galería de más de 450 servicios compatibles (Stripe, Slack, Postgres, OpenAI, Qdrant, GitHub, etc.).

5. **Tabla de Precios Transparente:**
   - Nivel Community (Gratis para siempre, self-hosted con ejecuciones ilimitadas).
   - Nivel Cloud Pro (Gestionado, alta disponibilidad).
   - Nivel Enterprise (SSO, SLA 99.99%, soporte dedicado).

6. **Preguntas Frecuentes (FAQ) Interactivas:**
   - Acordeones desplegables con respuestas clave sobre licencias y privacidad.

---

## 📂 Cómo ver la Landing Page

Puedes abrir directamente el archivo `index.html` en tu navegador web:

1. Haz doble clic en el archivo [index.html](file:///C:/Users/usuario/.gemini/antigravity/scratch/nexusflow-landing/index.html).
2. O ábrelo desde PowerShell:
   ```powershell
   Start-Process "C:\Users\usuario\.gemini\antigravity\scratch\nexusflow-landing\index.html"
   ```
