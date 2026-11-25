# Centro de Continuidad TIC · Interbank

Sistema web (prototipo operativo) del **Plan Estratégico de las TIC para Interbank**, desarrollado para el curso **Planeamiento Estratégico de las TICs** de la UTP.

Es una aplicación de una sola página, autocontenida, que materializa el plan (avances 1 y 2) como un centro de control de continuidad tipo NOC: muestra en vivo el estado de los servicios críticos, el Balanced Scorecard, la matriz de riesgos, el plan de recuperación (DRP) y la gobernanza de TI, todo trazable al documento.

## Cómo verlo

- **Abrir directo:** descarga `index.html` y ábrelo con doble clic en cualquier navegador (funciona sin internet).
- **Publicado (GitHub Pages):** una vez activado en *Settings → Pages → Branch: main → /(root)*, queda disponible en:
  `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Qué incluye

El sistema tiene 12 vistas que cubren las 3 unidades del sílabo:

- **Resumen general** — estado operativo, disponibilidad en vivo, riesgos y bitácora.
- **Continuidad** — 7 servicios críticos y simulador del incidente R1.
- **Recuperación (DRP)** — RTO/RPO por dominio, pasos del DRP, mitigación y madurez BCMM.
- **Estrategia (FODA)** — FODA, IFE/EFE y las 12 estrategias priorizadas.
- **Arquitecturas de TI** — funcional, de sistemas, de datos e infraestructura.
- **Plan de acción** — 17 tareas y cronograma de 8 meses (Gantt).
- **Gobierno de TIC** — órganos de gobierno, el CIO, ISO 38500 y COBIT.
- **Balanced Scorecard** — 6 objetivos SMART y 19 KPI.
- **Riesgos** — matriz de calor 5×5 y análisis actual vs. residual.
- **Proveedores** — terceros críticos con acceso a datos.
- **Outsourcing / TDR** — decisión de tercerización, TDR y expedientes.
- **Bitácora** — registro de eventos en vivo.

En la carpeta `entregables/` están la presentación (`.pptx`) y su versión en PDF.

## Stack

HTML5, CSS3 y JavaScript (sin dependencias ni build). Gráficos en SVG hechos a mano. Tipografía *Space Grotesk* + *Inter* (vía Google Fonts, con respaldo a la fuente del sistema si no hay internet).

## Nota sobre los datos

Las metas, la matriz de riesgos, los RTO/RPO, el presupuesto y la MPC provienen del plan (avances 1 y 2). Los valores de operación "en vivo" (disponibilidad, latencias, porcentaje de avance de cada KPI) están **simulados** para la demostración; en producción los alimentaría la telemetría y el BIA definidos en el plan.

## Autor

**Rodrigo Andree Coronel Carcasi** — U22208740
Ingeniería de Sistemas e Informática · Universidad Tecnológica del Perú (UTP)
Curso: Planeamiento Estratégico de las TICs · Sección 20750
