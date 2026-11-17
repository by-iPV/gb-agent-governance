# GB Agent Governance

Repositorio de gobernanza, normas versionadas y continuidad operativa de agentes GB, Emisarios G-PRO y Delegados ChatGPT.

## Propósito

Este repositorio funciona como canal versionado de publicación y continuidad para agentes que operan fuera de Notion, especialmente Emisarios G-PRO y sus Delegados ChatGPT.

### Alcance inicial

- Normas comunes para Emisarios G-PRO.
- Reglas específicas de ASDA.
- Contrato de coordinación ASDA ↔ Delegado ChatGPT.
- Continuidad entre fases mediante GitHub.
- Historial de cambios y versión publicada.

## Relación con Notion, DDH y PCA/IA

- **Notion** conserva la gobernanza interna, ER, DDH, LOG canónicos y minutas cuando PCA/IA lo requiera.
- **GitHub** es el canal versionado de publicación de normas para Emisarios y el buzón permanente ASDA ↔ Delegado.
- **Google Docs** queda como canal complementario cuando la actividad lo requiera; no es el único puente de continuidad.
- **Chat** sirve para activación y síntesis; no debe ser la única fuente de verdad.

Este repositorio **no sustituye**:
- DDH;
- ADELANTE π;
- gates;
- FIN DE FASE;
- LOG canónico cuando PCA/IA lo exige.

## Estado de esta publicación

**Versión:** 0.1.0-candidate  
**Base:** PLANTILLA_GPT_DELEGADO_BASE v2.1 + mejoras candidatas v2.2 documentadas en PMO + plantilla específica ASDA candidata v2.2.

La etiqueta **candidate** significa que contiene reglas preparadas para revisión/uso controlado y no debe interpretarse como modificación silenciosa de v2.1.

## Estructura

- `emisarios/REGLAS-GPRO.md` — normas comunes para Emisarios G-PRO.
- `emisarios/ASDA.md` — reglas específicas y continuidad de ASDA.
- `delegados/ASDA-DELEGADO.md` — contrato ASDA ↔ Delegado ChatGPT.
- `CHANGELOG.md` — historial de cambios.
- `VERSION` — versión publicada.

## Principio de plataforma

Las normas deben expresarse según las capacidades reales del destinatario.

Ejemplo: si un Emisario opera mediante GitHub, no se le instruye a documentar directamente en Notion. Se conserva el control equivalente en GitHub y el Delegado concilia con Notion/PCA cuando corresponda.

## Continuidad ASDA ↔ Delegado

GitHub será el buzón permanente ASDA ↔ Delegado.

Convención inicial:
- una **Issue por actividad/fase o incidencia**;
- comentarios append-only para seguimiento;
- referencias a LOG, PR, commit o evidencia;
- estado, siguiente acción y autorización claramente separados;
- el cierre de una Issue no equivale automáticamente a cierre PCA/IA.

## Seguridad y trazabilidad

- No publicar secretos, tokens ni credenciales.
- No publicar PII.
- No inferir autorizaciones.
- Conservar historial y versiones.
- No duplicar FIN DE FASE como señal ejecutable fuera de su fuente canónica.

## Gobierno de cambios

Un commit por sí solo no crea autorización HITL ni modifica automáticamente las reglas internas. Todo cambio normativo debe conservar referencia a su fuente, estado y decisión correspondiente.
