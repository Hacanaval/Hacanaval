# GitHub — Hugo Canaval (Hacanaval)

**Perfil:** https://github.com/Hacanaval  
**Última revisión:** 2026-04-21  
**Estado:** Actualizado — ver sección "README nuevo (listo para publicar)"

---

## Acciones inmediatas antes de publicar el README

### 1. Contribuciones privadas — NO aplica en este caso

GitHub tiene un toggle oficial "Private contributions" que muestra actividad anónima de repos privados.  
**Bloqueado:** la cuenta corporativa de Coordinadora y la cuenta personal `Hacanaval` son cuentas separadas por políticas de seguridad de la empresa. El toggle solo funciona cuando los commits vienen de la misma cuenta.

**Alternativa verificada: ghost-commits**  
GitHub Action open source (MIT) que extrae solo metadatos sanitizados de repos privados y los publica en un repo público. Sin código, sin nombres internos — solo la evidencia de que la actividad existe.  
Ver detalle completo en `docs/buenas-practicas-perfil-tech.md` → sección 2.2.

### 2. Corregir el link del CV
El README actual apunta a `cv-hugo-canaval.lovable.app` — link desactualizado.
**URL correcta y activa:** `https://cv-hugo-canaval.vercel.app/` — ya corregida en el README nuevo.

---

## Reglas para mencionar trabajo corporativo (fuentes: Kickresume, StackExchange Workplace)

| Puedes incluir | No debes incluir |
|----------------|-----------------|
| Nombre de la empresa (es experiencia laboral) | Nombres internos de sistemas o proyectos bajo NDA |
| Las tecnologías que usaste | Código propietario o arquitecturas con detalle |
| Métricas de resultado (% mejora, escala, ahorro) | Datos financieros internos de la empresa |
| El tipo de problema que resolviste | Nombres de clientes internos |

**Formulación que funciona:**
> "Developed a [tipo de sistema] at [Empresa] to solve [tipo de problema], using [stack], resulting in [métrica]."

Los proyectos corporativos son TU trabajo — que el código sea propiedad de la empresa no te quita el mérito.

---

## README actual (versión original)

```markdown
Hi there, I'm Hugo Canaval! 👋
A passionate Data Scientist with a strong foundation in Machine Learning and Artificial Intelligence.
I apply data-driven strategies and business insights to solve complex problems and drive growth.

🛠️ Skills & Expertise
- Programming Languages: Python, SQL
- Machine Learning: Predictive modeling, classification, regression, clustering.
- Data Analysis & Visualization: Pandas, NumPy, Matplotlib, Seaborn.
- Data-Driven Strategy: Development and implementation of insight-driven strategies.
- Business Intelligence & Analytics: Report generation, KPI analysis, opportunity identification.

💼 About Me
A results-oriented professional transitioning from a successful career in the consumer goods industry
(BAT, Anheuser-Busch InBev, Mondelēz, Nielsen) where I developed strong skills in data analysis,
strategic thinking, and digital transformation. I am now fully immersed in the world of Data Science,
eager to apply my analytical abilities and business acumen to extract meaningful insights and build
impactful solutions. My experience in sales, trade marketing, and category management has provided me
with a unique perspective on leveraging data to drive business growth and improve decision-making.

🔗 Let's Connect!
https://www.linkedin.com/in/hugo-canaval/
https://cv-hugo-canaval.lovable.app/
```

---

## Repositorios públicos actuales

| Repositorio | Descripción | Stack |
|-------------|-------------|-------|
| `agente_vendedor_backend` | SaaS Sales Chatbot multitenante | FastAPI, PostgreSQL, FAISS, LLM, JWT |
| `ride-demand-timeseries` | Forecast demanda taxis por hora | Scikit-learn, XGBoost, SARIMA, Prophet |

---

## Problemas del README actual

1. **Stack desactualizado:** No menciona GCP (BigQuery, Cloud Run, Gemini) — el núcleo del trabajo real
2. **Sin proyectos de producción:** Los 8 proyectos de Coordinadora no son públicos pero el README debería reflejar el tipo de trabajo que se hace
3. **"Transitioning" ya no aplica:** Ya no está en transición — está construyendo sistemas en producción
4. **CV web desactualizado:** Link apunta a `lovable.app` — debería ser `cv-hugo-canaval.vercel.app`
5. **Sin métricas de impacto:** No comunica escala ni impacto real (100M+ filas, $50K/semana)
6. **Poco diferenciador:** Descripción genérica que aplica a cualquier Data Scientist junior

---

## README nuevo (listo para publicar)

```markdown
# Hi, I'm Hugo Canaval

Data Scientist designing and deploying ML and AI systems in production environments.
I bring a business-first perspective to data problems — I came from 6+ years in commercial
strategy before going deep into engineering, and that combination shapes how I build.

---

## What I build

Most of my production work lives in private repositories, but here's the kind of systems I design and deploy:

- **Predictive ML at scale** — delivery probability model trained on 103M+ records at Coordinadora,
  reducing operational costs by ~15% (~$50K USD/week in logistics savings)
- **Multi-agent AI systems** — Cloud Run + Gemini for automated operational reporting across 8+ data sources
- **Document intelligence pipelines** — Gemini Vision for invoice OCR + automatic bank reconciliation
- **Production APIs** — FastAPI services on Cloud Run consuming BigQuery at scale
- **LLM validation systems** — automated photo evidence verification with Gemini Vision

---

## Stack

```
ML & Data      Python · Scikit-learn · XGBoost · Pandas · NumPy · PySpark
Cloud (GCP)    BigQuery · Cloud Run · Gemini API · Cloud Storage · gcloud CLI
Backend        FastAPI · Docker · JWT · PostgreSQL
LLMs & AI      Gemini · Prompt Engineering · RAG · FAISS · BERT/TF-IDF
Other          Git · Telegram Bot API · Google Sheets API
```

---

## Public projects

Projects in this profile are from my data science training program (TripleTen bootcamp, 2024–2025).
They reflect the foundations; the production work is confidential.

- [**SaaS Sales Agent**](https://github.com/Hacanaval/agente_vendedor_backend) — Multi-tenant chatbot backend with RAG, FAISS vector search, FastAPI + JWT
- [**Taxi Demand Forecast**](https://github.com/Hacanaval/ride-demand-timeseries) — Hourly demand prediction comparing SARIMA, XGBoost, Prophet

---

## Background

Before engineering, I spent 6+ years in commercial roles at BAT, AB InBev, Mondelēz, and Nielsen —
pricing strategy, category management, trade marketing. That gave me something most data scientists
don't have: a working understanding of what a business decision actually costs.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-hugo--canaval-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/hugo-canaval)
[![CV](https://img.shields.io/badge/CV-Online-brightgreen?style=flat)](https://cv-hugo-canaval.vercel.app/)

📍 Cali, Colombia · hacanaval@hotmail.com
```

---

## Decisiones de diseño del README nuevo

| Decisión | Justificación |
|----------|--------------|
| Sin "transitioning" | Ya no aplica — lleva más de un año construyendo sistemas en producción |
| Mencionar Coordinadora con métricas | Es experiencia laboral legítima. Las métricas son tuyas |
| Sección "Most of my production work lives in private repos" | Honesto y profesional — explica por qué el perfil público parece escaso |
| Proyectos públicos presentados como "bootcamp foundations" | Verdad — no los sobrevendas como si fueran producción |
| Stack con formato de tabla monoespaciada | Más legible, diferente al formato genérico de bullet points |
| Sin emojis excesivos | Un emoji de header está bien; el exceso es señal de perfil junior |

---

## Decisiones pendientes antes de publicar

- [ ] Confirmar si se puede mencionar Coordinadora explícitamente (empresa privada)
- [ ] Decidir si subir algún proyecto de Coordinadora como ejemplo anonimizado
- [x] ~~Actualizar link de CV web~~ — ya corregido a `cv-hugo-canaval.vercel.app`
- [ ] Verificar qué repositorios son públicos actualmente
- [ ] Agregar GitHub Actions badges si hay CI activo en repos públicos
