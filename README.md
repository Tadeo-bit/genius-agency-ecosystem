# Ecosistema de Gestión Digital - Genius Agency 🚀

Este repositorio centraliza y documenta la arquitectura de microservicios desarrollada de forma colaborativa durante un sprint de 5 semanas para nuestro cliente **SueñoSimple**. El objetivo del proyecto fue resolver problemas críticos de conversión, inestabilidad técnica y falta de visibilidad de datos en campañas masivas.

---

## 🗺️ Arquitectura del Ecosistema

El proyecto fue diseñado bajo una arquitectura cliente-servidor e integración de microservicios locales que se comunican de forma asíncrona mediante APIs (formatos JSON). El ecosistema se compone de 4 módulos independientes:

1. **Genius Landings (Frontend Estático):** Páginas de aterrizaje de alta conversión desarrolladas en HTML, CSS y JavaScript puro para campañas masivas.
2. **Landing CRM (API Rest - Node.js):** Microservicio encargado del procesamiento, registro y persistencia temporal de los leads capturados.
3. **Genius Dashboard (Frontend - React):** Panel de control interno para la visualización de métricas en tiempo real y gráficos de rendimiento de campañas.
4. **Budget Manager (Backend - Java):** Componente dedicado a la gestión financiera y asignación de presupuestos por cliente.

---

## 💻 Mi Contribución Técnica (Frontend & UX/UI)

Como **Líder de Desarrollo Frontend & UX**, mis principales aportes al proyecto incluyeron:

* **Desarrollo desde el Prototipo:** Creación e implementación integral de las landings para las campañas del *Mundial* y *Día de la Madre*, respetando la identidad visual corporativa de la marca.
* **Optimización de Conversión y Estabilidad:** Diagnóstico y reparación de bugs críticos en código heredado (botones de conversión rotos).
* **Lógica Anti-Doble Clic:** Programación de un script en JavaScript para bloquear los formularios tras el primer envío, evitando la inyección de registros duplicados en la API del CRM y protegiendo el servidor de peticiones redundantes.
* **Plan de Contingencia (UX):** Integración de desvíos inteligentes a WhatsApp para asegurar la captura del cliente ante posibles fallos de red.
* **Metodologías Ágiles y Handoff:** Co-autoría del documento final de *Handoff* técnico en la rama `dev`, incluyendo la propuesta formal para la migración de datos hacia PostgreSQL para eliminar la volatilidad "In-memory".

---

## 🔗 Repositorios del Proyecto

A continuación se detallan los accesos a cada uno de los componentes modulares desarrollados por la célula de ingeniería:

* 📄 [Módulo Frontend: Genius Landings](REEMPLAZAR_CON_LINK_DEL_REPO_DE_LANDINGS)
* ⚙️ [Módulo API: Landing CRM](REEMPLAZAR_CON_LINK_DEL_REPO_DEL_CRM)
* 📊 [Módulo Panel: Genius Dashboard](REEMPLAZAR_CON_LINK_DEL_REPO_DEL_DASHBOARD)
* ☕ [Módulo Backend: Budget Manager](REEMPLAZAR_CON_LINK_DEL_REPO_DEL_BUDGET)

---

## 👥 Célula de Desarrollo (Genius Agency)
* **Tadeo Otaola** - Líder de Desarrollo Frontend & UX
* **Alejandro** - Analista de Datos / Data Specialist
* **Cristian** - Desarrollador Backend
* **Román** - Desarrollador Backend
