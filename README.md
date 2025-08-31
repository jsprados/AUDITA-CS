# 🕵️‍♀️ AUDITA-CS
**Auditoría Ciudadana de Sistemas de IA en la Administración Pública Española**

![Logo del proyecto](docs/logo_audita.png)

---

## 📌 Descripción
El rápido despliegue de la inteligencia artificial en la Administración Pública plantea riesgos de **opacidad, sesgo y falta de rendición de cuentas**.  
**AUDITA-CS** propone una plataforma socio-técnica **open source** para que ciudadanía y personal público puedan **auditar de forma participativa** los algoritmos utilizados en servicios públicos.

Este proyecto se desarrolla en el marco de la **Convocatoria I+P 2025 (FECYT)**, categoría A (*proyectos singulares para innovación en políticas públicas*), con financiación solicitada de **100.000 € (90% del presupuesto total)**:contentReference[oaicite:0]{index=0}.

---

## 🎯 Objetivos
### Objetivo general
Co-diseñar, desarrollar y validar una plataforma de **auditoría algorítmica participativa** que refuerce la transparencia, equidad y responsabilidad de los sistemas de IA utilizados en la Administración Pública española:contentReference[oaicite:1]{index=1}.

### Objetivos específicos
1. **Marco metodológico participativo**: definición de criterios de equidad y protocolos claros para auditorías ciudadanas.  
2. **Plataforma open source (BiasAudit Tool ES)**: software con módulos de *fairness* y *explainability* (LIME, SHAP, contrafactuales).  
3. **Validación en pilotos reales**: tres estudios piloto con AAPP colaboradoras (El Ejido, Diputación de Almería, Junta de Andalucía).  
4. **Análisis y recomendaciones**: informes comparativos con hallazgos y propuestas de mejora.  
5. **Diseminación y transferencia**: Guía de Buenas Prácticas, policy briefs y artículos científicos:contentReference[oaicite:2]{index=2}.

---

## 🏛️ Entidades participantes
- **Entidad solicitante:** Universidad de Almería  
- **Administraciones colaboradoras:**  
  - Ayuntamiento de El Ejido  
  - Diputación de Almería  
  - Junta de Andalucía  

> La colaboración se formaliza mediante cartas de compromiso firmadas por cada AAPP, según modelo oficial de la convocatoria:contentReference[oaicite:3]{index=3}.

---

## 🗂️ Paquetes de trabajo (WP)
- **WP1** – Co-diseño del marco de auditoría participativa  
- **WP2** – Desarrollo de la plataforma tecnológica AUDITA-CS  
- **WP3** – Validación en pilotos reales  
- **WP4** – Análisis de resultados y recomendaciones  
- **WP5** – Diseminación y transferencia  
- **WP6** – Gestión, gobernanza y sostenibilidad:contentReference[oaicite:4]{index=4}

---

## 📅 Cronograma
Duración: **24 meses** (2025–2027).  
- M0–M6: Marco metodológico (WP1)  
- M4–M15: Desarrollo de la plataforma (WP2)  
- M10–M20: Pilotos (WP3)  
- M18–M22: Ajustes y validación final (WP4)  
- M20–M24: Diseminación y explotación (WP5–WP6)

---

## ⚖️ Cumplimiento normativo
El proyecto se alinea con:  
- **AI Act (Reglamento Europeo de IA 2024/1689)** – clasificación de sistemas de alto riesgo, supervisión humana y trazabilidad.  
- **RGPD y LOPDGDD** – protección de datos personales.  
- **ENS/ENI** – seguridad y transparencia en servicios públicos digitales.  
- **EUPL-1.2** – licencia de software recomendada para AAPP en España.

---

## 📖 Documentación
- [Memoria técnica](docs/memoria_tecnica.pdf)  
- [Guía metodológica v1.0](docs/guia_metodologica.pdf)  
- [Modelo de carta de colaboración AAPP](docs/carta_colaboracion.pdf)  

---

## 🔧 Instalación (versión preliminar)
```bash
git clone https://github.com/usuario/audita-cs.git
cd audita-cs/src
pip install -r requirements.txt
