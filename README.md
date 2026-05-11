# 📞 Auditoría de Eficacia Operativa: Proyecto "CallMeMaybe"

**Data Analytics & Strategic Consulting | Diagnóstico de Desempeño Operativo**

---

## 🔗 Ecosistema del Proyecto
*   **[📊 Dashboard Interactivo en Tableau](https://public.tableau.com/views/ElPuntoCrticoDiagnsticodeProductividadenEquiposMixtos/AuditoradeDesempeoOperativo?:language=es-ES&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)**
*   **[📄 Presentación Ejecutiva (PDF)](./reports/Presentacion_CallMeMaybe.pdf)**
*   **[💼 Post de Discusión en LinkedIn](https://www.linkedin.com/posts/gersonv-bda_dataanalytics-businessintelligence-python-activity-7459461862229725184-H9Tl)**

---

## 🎯 Objetivo y Alcance
Desarrollo de un modelo de diagnóstico para identificar fracturas en la productividad de **1,092 operadores únicos**. El análisis trasciende la métrica plana, aplicando rigor estadístico para separar la variabilidad natural del bajo rendimiento sistemático.

## 🚀 Hallazgo Crítico: El Colapso del Modelo "Mixed"
> La ineficacia global es del **25.27%**, pero el análisis granular reveló un epicentro de riesgo: el segmento **Mixed** presenta un **59.17% de ineficacia**. La polivalencia (saltar entre flujos In/Out) está destruyendo la calidad del servicio, validado mediante una correlación masiva de **$r = 0.82$** entre volumen y duración de gestión.

---

## 🧠 Metodología Avanzada (Data Literacy)

### 1. Umbrales Dinámicos (Valla de Tukey)
Se abandonaron los promedios rígidos para implementar límites basados en la distribución real de los datos:
*   **Productividad:** < 3.35 llamadas/día.
*   **Disponibilidad (Espera):** > 45 segundos.

### 2. Validación Científica
*   **Prueba T (Volumen):** Diferencia significativa entre Eficaces (30.29) vs. Ineficaces (1.76).
*   **Efecto Cohen’s d (0.61):** Magnitud de impacto moderada-alta en la duración de las llamadas.
*   **Chi-Cuadrado ($p = 0.1378$):** Se confirmó que el plan tarifario **no influye** en la ineficacia; el problema es puramente operativo/RRHH.

---

## 🛠️ Stack Tecnológico
*   **Lenguaje:** Python 3.x (Pandas, NumPy, Scipy, Statsmodels).
*   **Entorno:** WSL (Ubuntu) en MSI Workstation + Docker.
*   **Visualización:** **Tableau Public** para el análisis de "Punto Crítico" y Seaborn para la exploración estadística.
*   **Automatización:** Google Apps Script para la generación de reportes profesionales.

---

## 📂 Estructura del Repositorio
*   `notebooks/`: Proceso ETL, análisis estadístico y validación de hipótesis.
*   `data/`: Estructura de datos procesados (Bases consolidadas).
*   `reports/`: Reporte ejecutivo con la narrativa estratégica para stakeholders.

---

## 🧑‍💻 Sobre mí
**Gerson A. Vázquez** – Bioengineer & Data Analyst.
Especializado en transformar datos complejos en decisiones quirúrgicas. 
*   **LinkedIn:** [Conectemos](https://www.linkedin.com/in/gersonv-bda/)