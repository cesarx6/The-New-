# Portafolio de Análisis de Datos — Flavio César Ortiz Santos

Analista de datos enfocado en transformar información en decisiones.

Los proyectos de este portafolio abordan problemas reales de negocio mediante procesos estructurados de limpieza, validación y análisis de datos. Cada uno sigue el marco OSEM (Objetivo → Sistema → Exploración → Modelo) y se comunica en formato C→F→I (Contexto → Hallazgos → Implicaciones).

**Herramientas:** Excel avanzado · SQL (PostgreSQL, MySQL) · Python (pandas, NumPy, scikit-learn · seaborn · matplotlib)

---

## Proyectos

### 1. Análisis de Movilidad Urbana y Productividad Económica en LATAM
**· TripleTen . **

Evalué la relación entre congestión vehicular y PIB per cápita en 10 ciudades latinoamericanas usando datos reales de TomTom Traffic Index y OECD Cities 2024.

- Integré y limpié un dataset de 1,004,464 registros de tráfico con datos económicos de 30 ciudades
- Apliqué normalización MinMax para comparar variables de diferente escala en una misma visualización
- **Hallazgo principal:** correlación negativa entre congestión y productividad — Ciudad de México lidera con 2,702 min de retraso promedio y uno de los PIB per cápita más bajos de la muestra; Brasilia muestra el patrón inverso (96 min · $16,251 USD/cápita)

`Python` `pandas` `NumPy` `scikit-learn` `seaborn` `matplotlib` `Jupyter Notebook`

---

### 2. Resumen Ejecutivo de Ventas — Walmart 2012
**· TripleTen **

Analicé el desempeño comercial de 45 tiendas y 15 departamentos para responder dos preguntas de la Dirección Comercial: eficiencia por metro cuadrado y participación por categoría.

- Integré 3 tablas raw en un dataset limpio con dashboard interactivo y tabla dinámica
- Construí KPIs de eficiencia (ventas/m²) y participación (ventas depto / ventas totales)
- **Hallazgo principal:** Despensa y Básicos lideró en volumen ($85M · 15.29% del total) y eficiencia (227.49%); brecha de 13x entre el departamento más y menos eficiente

`Excel avanzado` `Tablas dinámicas` `Dashboard interactivo` `VLOOKUP` `KPIs`

---

### 3. Análisis de Desempeño Financiero con SQL
**TripleTen**

Analicé ingresos, costos, margen operativo y ROI de campañas de marketing en 6 mercados internacionales para responder preguntas estratégicas de la Dirección Financiera.

- Consolidé datos de 4 tablas relacionales mediante JOIN y LEFT JOIN con manejo de nulos vía COALESCE
- Calculé KPIs financieros (beneficio bruto, margen %, ROI de campaña) usando NULLIF para evitar errores de división
- **Hallazgo principal:** USA lidera en ROI de campaña (75.75%) mientras Canadá tiene el mayor margen operativo (44.76%) con el menor ingreso — evidencia de eficiencia operativa sin respaldo publicitario efectivo
- Modelé escenario: +50% en inversión publicitaria proyectaría el ROI de USA a ~50.50%

`SQL` `PostgreSQL` `COALESCE` `NULLIF` `KPIs financieros` `Excel`

---


## Contacto

- **Email:** csaraf127@gmail.com
- **LinkedIn:** linkedin.com/in/flavio-césar-ortiz-santos5738633b9/
- **Certificación:** Análisis de Datos · TripleTen · 2025–2026
