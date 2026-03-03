# Business Analytics Simulation – Dynamics 365 & Power BI

## Descripción del proyecto
Este proyecto es una simulación de **análisis comercial regional** utilizando datos industriales sintéticos basados en el INE y extendidos en **Dynamics 365 Sales** (Dataverse).  
El objetivo es mostrar cómo transformar datos operativos en información estratégica para la **toma de decisiones comerciales** mediante dashboards ejecutivos en **Power BI**.

Los datos utilizados pueden consultarse en https://www.ine.es/jaxi/Tabla.htm?tpx=78902

---

## Objetivos del proyecto
- Integrar datos de cuentas y regiones en un entorno Dynamics 365 Sales.  
- Normalizar y preparar indicadores de ingreso estimado y producción industrial.  
- Analizar el desempeño regional y priorizar cuentas según potencial.  
- Crear visualizaciones ejecutivas que faciliten la interpretación rápida de KPIs clave.

---

## Datos utilizados
- **Fuente:** Datos públicos del INE (modificados para fines de simulación).  
- **Tabla principal:** `Account` en Dataverse  
- **Columnas relevantes:**
  - `Región`: Comunidad autónoma española
  - `Nombre Cuenta`: Nombre de la cuenta
  - `Índice Producción Industrial`: Valor original del INE
  - `Índice Normalizado`: Normalización para análisis comparativo utilizando min-max scaling
  - `Ingreso Estimado`: Creado dividiendo índice entre 5
  - `Clasificación Potencial`: Alto / Medio / Bajo (para segmentación)

---

## Herramientas
- **Dynamics 365 Sales (Dataverse):** Gestión y modelado de datos de cuentas.  
- **Power BI Desktop:** Creación de medidas DAX, visualizaciones y dashboard ejecutivo.  
- **Excel:** Datos originales y generación de dataset sintético.

---

## Medidas y KPIs implementados
- **IngresoTotal:** Suma de ingreso estimado por cuenta/región.  
- **PromedioIngreso:** Promedio de ingreso estimado.  
- **TotalCuentas:** Número total de cuentas analizadas.  
- **PorcentajeRegion:** Contribución porcentual de cada región al ingreso total.  
- **DiferenciaVsTop:** Diferencia de ingreso respecto a la región líder.  

---

## Visualizaciones principales
- **KPI Cards:** Total de ingresos e Ingresos Promedio.  
- **Gráfico de barras:** Ingreso por región, ordenado de mayor a menor.  
- **Pie Chart:** Aporte porcentual por región al total de Ingresos.  

---

## Insights clave
- Algunas regiones concentran la mayor parte del ingreso estimado.  
- Existen brechas notables respecto a la región líder, que identifican oportunidades comerciales.  
- El dashboard facilita la toma de decisiones basada en datos y la planificación comercial regional.

---

## Uso del proyecto
1. Abrir el archivo `Dashboard.pbix` en **Power BI Desktop**.  
2. Explorar los KPIs, gráficos y slicers interactivos.  
3. Analizar la contribución por región y el Top 10 de cuentas.  
4. Adaptar la simulación con datos reales si se dispone de un entorno Dynamics 365 Sales completo.

---

## Notas adicionales
- Este proyecto es **sintético y educativo**, enfocado en demostrar competencias de Business Analytics con Dynamics 365 y Power BI.  
- Los datos y visualizaciones se pueden usar para **portfolio profesional**, CV o entrevistas.  

---

## Autor
**Allan Villarreal** – Analista de Datos en formación
