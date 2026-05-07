# 📞 Análisis de Eficacia Operativa: Caso CallMeMaybe

**Proyecto Final de Análisis de Datos | Especialidad en Consultoría Estratégica**

---

## 🎯 Objetivo del Proyecto

Desarrollar un modelo de diagnóstico robusto para identificar operadores ineficaces en el servicio de telefonía virtual. El análisis se centra en tres dimensiones críticas: tasas de llamadas perdidas, tiempos de espera excesivos y productividad en llamadas salientes.

## 🪝 Hallazgo Clave (Executive Summary)

> Se identificó un núcleo crítico de **159 operadores ineficaces** (20.5% de la fuerza activa). Mediante pruebas de inferencia estadística, se confirmó una diferencia masiva en su gestión del tiempo (**p-value < 0.05**), descartando factores de azar y validando la necesidad de una intervención operativa inmediata.

## 🧠 Metodología: El Enfoque de Segmentación Operativa

Para garantizar la equidad en la evaluación, este proyecto aplica una **segmentación por perfiles funcionales** basada en literatura de gestión de operaciones (**Gans et al., 2003**):

* **Inbound:** Especialistas en recepción (Enfoque en tiempo de espera y llamadas perdidas).
* **Outbound:** Especialistas en emisión (Enfoque en volumen de prospección).
* **Mixed:** Operadores polivalentes con umbrales ajustados.

## 🛠️ Stack Tecnológico

* **Entorno de Desarrollo:** WSL (Ubuntu) en MSI Workstation.
* **Lenguaje:** Python 3.x.
* **Análisis de Datos:** Pandas, NumPy, Scipy (Inferencia Estadística).
* **Visualización:** Matplotlib, Seaborn y **Tableau Public** (Dashboard Interactivo)[cite: 1].

## 📂 Estructura de Entregables

* **`notebooks/`:** EDA, ingeniería de variables y validación de hipótesis.
* **`data/`:** Datasets procesados y listos para BI[cite: 1].
* **`reports/`:** Conclusiones estratégicas y capturas del Dashboard.

## 🔬 Rigor Estadístico

El proyecto incluye pruebas de normalidad y varianza (**Levene & t-test**) para asegurar que las etiquetas de "ineficacia" correspondan a patrones de comportamiento técnico y no a fluctuaciones aleatorias del volumen de llamadas.
