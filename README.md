# TelecomX: Estrategias de Retención basadas en Data Science

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)

> **Status del Proyecto:** La empresa TelecomX enfrenta una tasa crítica de deserción del **26.58%**. Este análisis transforma datos crudos en estrategias accionables para frenar la fuga de clientes.

---

## Objetivos del Proyecto

El propósito de este análisis es desglosar el ecosistema de datos de TelecomX para:
* **Identificar** los disparadores (*triggers*) técnicos y demográficos del Churn.
* **Cuantificar** el impacto financiero de la pérdida de clientes en el ciclo de vida inicial.
* **Diseñar** una hoja de ruta estratégica para los departamentos de Marketing y Customer Success.

---

## Hallazgos Clave (Data Insights)

El análisis exploratorio de datos (EDA) reveló tres pilares de vulnerabilidad:

### 1. El Factor "Tiempo y Compromiso"
* **El Mes Crítico:** La deserción alcanza su pico máximo durante los primeros 30 días de servicio.
* **Volatilidad Contractual:** Los contratos **Mes a Mes** presentan una tasa de fuga del **42.71%**, comparado con solo el 2.85% de los contratos bienales.


### 2. Infraestructura y fricción de Pago
* **Crisis en Fibra Óptica:** A pesar de ser la tecnología de punta, el **41.89%** de sus usuarios abandonan, sugiriendo una brecha entre el alto costo y la estabilidad percibida.

* **Fricción Financiera:** El **Cheque Electrónico** es el método de pago con mayor tasa de abandono (45.29%), vinculado a procesos de pago manuales y falta de automatización.

### 3. Segmentación Demográfica
* **Riesgo Senior:** Los adultos mayores (65+) tienen un riesgo de fuga del **41.68%**.
* **Baja Vinculación Familiar:** Los clientes solteros y sin dependientes son el segmento más volátil y numeroso.

---

## Recomendaciones Estratégicas

Basado en la evidencia, se proponen las siguientes acciones:

| Estrategia | Acción Táctica | Impacto Esperado |
| :--- | :--- | :--- |
| **Onboarding 360** | Llamadas de cortesía a los 15 días + Descuentos progresivos (Mes 1-3). | Reducción del Churn temprano. |
| **Migración de Pago** | Incentivos para pasar de Cheque Electrónico a Débito Automático. | Estabilización del flujo de caja. |
| **Bundling de Valor** | Empaquetar Fibra Óptica con servicios de valor agregado (Streaming). | Mejora en la percepción de valor/precio. |
| **Soporte Silver** | Canal de atención humana y simplificada para Adultos Mayores. | Fidelización del segmento de alto riesgo. |

---

## Stack Tecnológico

* **Ingesta de Datos:** `Requests` (Extracción directa desde repositorio remoto JSON).
* **Procesamiento:** `Pandas` (Normalización de JSON anidados y limpieza de nulos).
* **Visualización Interactiva:** `Plotly Express`.
* **Análisis Estadístico:** `Seaborn` & `Matplotlib`.

---
