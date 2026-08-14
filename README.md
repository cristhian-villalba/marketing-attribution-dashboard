# 👑 Cuadro de Mando de Atribución Multicanal y Análisis de ROI

## 📝 Descripción del Proyecto
Este proyecto consiste en el desarrollo de una solución integral de Business Intelligence diseñada para centralizar, consolidar y auditar la inversión publicitaria en múltiples canales digitales (Google Ads, Meta Ads, campañas de Email Marketing) e integrarla con los datos de conversión del CRM.

El objetivo principal es resolver la fragmentación del dato publicitario, permitiendo a la dirección comercial y de marketing evaluar el **Retorno de la Inversión (ROI)**, el **Coste Por Lead (CPL)** y la efectividad del embudo de ventas en una única fuente de verdad.

---

## 📊 Impacto de Negocio y Resultados Clave

* **Centralización Multicanal:** Consolidación de datos heterogéneos de inversión publicitaria y atribución de ventas en un modelo de datos unificado.
* **Optimización del Presupuesto:** Identificación precisa del canal con menor **Coste Por Lead (CPL)** y mayor tasa de conversión a cliente final.
* **Lógica de Atribución en DAX:** Implementación de métricas calculadas complejas mediante funciones **DAX** para el cálculo del ROI en tiempo real y análisis comparativo temporal (*Time Intelligence*).
* **Visibilidad Ejecutiva:** Creación de un lienzo interactivo con KPIs de inversión total, volumen de prospectos generados, coste de adquisición y margen de rentabilidad por campaña.

---

## 🛠️ Stack Tecnológico Utilizado

| Área | Tecnología / Herramienta | Aplicación en el Proyecto |
| :--- | :--- | :--- |
| **Orígenes de Datos** | SQL / Excel / APIs CRM | Datos de inversión publicitaria (Google Ads, Meta) y registros transaccionales/leads de CRM. |
| **Ingeniería de Datos (ETL)** | Power Query | Limpieza de tablas, unificación de formatos de moneda, eliminación de duplicados y modelado de datos. |
| **Modelado de Datos** | Power BI (Star Schema) | Construcción de un esquema en estrella (*Star Schema*) conectando tablas de hechos de inversión/ventas con dimensiones de tiempo, canal y campaña. |
| **Métricas & Cálculo** | DAX Avanzado | Cálculo de ROI, CPL, Tasa de Conversión y análisis *Year-over-Year* (YoY) mediante funciones de *Time Intelligence*. |

---

## 📂 Archivos del Repositorio

---

## 🎬 Vista Previa e Interactividad

![Demostración interactiva del Dashboard](demo_dashboard.gif)

> 📥 **Acceso al proyecto completo (.pbix):**  
> Puedes descargar el archivo ejecutable de Power BI para explorar el modelo de datos y las medidas DAX desde el siguiente enlace:  
> 🔗 **[Descargar archivo en Google Drive](https://drive.google.com/file/d/1W-EVClW4jx1tciCdP7a53teQZSkxCa_a/view?usp=sharing)**

---


* `Marketing_Attribution_Dashboard.pbix`: Archivo interactivo de Power BI con el modelo relacional, las medidas DAX y el diseño del reporte.
* `dataset_marketing_attribution.xlsx`: Conjunto de datos limpios de inversión y conversión utilizados para alimentar el modelo.

---

## 🚀 Cómo Replicar este Proyecto

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/cristhian-villalba/marketing-attribution-dashboard.git](https://github.com/cristhian-villalba/marketing-attribution-dashboard.git)
