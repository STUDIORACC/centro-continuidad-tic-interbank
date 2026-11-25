# Centro de Continuidad TIC · Interbank

Sistema web (prototipo operativo) del **Plan Estratégico de las TIC para Interbank**, desarrollado para el curso **Planeamiento Estratégico de las TICs** de la UTP.

Es una aplicación de una sola página, autocontenida, que materializa el plan (avances 1 y 2) como un centro de control de continuidad tipo NOC: muestra en vivo el estado de los servicios críticos, el Balanced Scorecard, la matriz de riesgos, el plan de recuperación (DRP) y la gobernanza de TI, todo trazable al documento.

## Cómo verlo

- **Abrir directo:** descarga `index.html` y ábrelo con doble clic en cualquier navegador (funciona sin internet).
- **Publicado (GitHub Pages):** una vez activado en *Settings → Pages → Branch: main → /(root)*, queda disponible en:
  `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Qué incluye

El sistema tiene 13 vistas que cubren las 3 unidades del sílabo:

- **Resumen general** — estado operativo, disponibilidad en vivo, riesgos y bitácora.
- **Continuidad** — 7 servicios críticos y simulador del incidente R1.
- **Recuperación (DRP)** — RTO/RPO por dominio, pasos del DRP, mitigación y madurez BCMM; lineamientos DRII, BCI e ISO 22301; roles y procedimiento de activación; gestión de crisis y gobierno del plan; documentación y plan de pruebas.
- **Estructura del PESI** — la empresa como sistema, alineación estratégica, las 8 partes de un PESI, gerencia de SI y recursos internos.
- **Estrategia (FODA)** — FODA, IFE/EFE y las 12 estrategias priorizadas.
- **Arquitecturas de TI** — funcional, de sistemas, de datos e infraestructura.
- **Plan de acción** — 17 tareas y cronograma de 8 meses (Gantt).
- **Gobierno de TIC** — órganos de gobierno, el CIO, ISO 38500, COBIT, tipos de gobierno y tipos de organización por tamaño y rubro.
- **Balanced Scorecard** — 6 objetivos SMART y 19 KPI.
- **Riesgos** — matriz de calor 5×5 y análisis actual vs. residual.
- **Proveedores** — terceros críticos con acceso a datos.
- **Outsourcing / TDR** — decisión de tercerización, insourcing, outsourcing y crowdsourcing, TDR y expedientes.
- **Bitácora** — registro de eventos en vivo.

## Cobertura del sílabo

| Unidad | Temas | Dónde está |
|---|---|---|
| 1. Planeamiento estratégico de las TI | Empresa como sistema, estrategia de SI, estructura de un PESI, gerencia de SI, recursos internos | Estructura del PESI |
| | Indicadores de gestión y Balanced Scorecard | Balanced Scorecard |
| | Arquitecturas funcional, de sistemas, de datos e infraestructura | Arquitecturas de TI |
| | Insourcing, outsourcing, crowdsourcing, TDR, expedientes y contratos | Outsourcing / TDR |
| 2. Gestión de la continuidad de negocio | Programa de continuidad, amenazas y riesgos, BIA | Continuidad, Riesgos |
| | DRII, BCI e ISO; ISO 22301 | Recuperación (DRP) |
| | Roles, estrategias de recuperación, crisis y desastres, gobierno del plan | Recuperación (DRP) |
| | Documentación, plan de pruebas y ejercicios; madurez BCMM | Recuperación (DRP) |
| 3. Gobierno de TIC | Gobierno corporativo, tipos de gobierno, órganos y el CIO | Gobierno de TIC |
| | ISO 38500, principios de COBIT y su implementación | Gobierno de TIC |
| | Tipos de organización por tamaño y rubro | Gobierno de TIC |

En la carpeta `entregables/` están la presentación (`.pptx`) y su versión en PDF.

## Stack

HTML5, CSS3 y JavaScript (sin dependencias ni build). Gráficos en SVG hechos a mano. Tipografía *Space Grotesk* + *Inter* (vía Google Fonts, con respaldo a la fuente del sistema si no hay internet).

## Nota sobre los datos

Las metas, la matriz de riesgos, los RTO/RPO, el presupuesto y la MPC provienen del plan (avances 1 y 2). Los valores de operación "en vivo" (disponibilidad, latencias, porcentaje de avance de cada KPI) están **simulados** para la demostración; en producción los alimentaría la telemetría y el BIA definidos en el plan.

## Autor

**Rodrigo Andree Coronel Carcasi** — U22208740
Ingeniería de Sistemas e Informática · Universidad Tecnológica del Perú (UTP)
Curso: Planeamiento Estratégico de las TICs · Sección 20750
