# GB Agent Governance

Repositorio de gobernanza, normas versionadas y continuidad operativa de agentes GB, Emisarios G-PRO y Delegados ChatGPT.

## Propósito

Este repositorio funciona como canal versionado de publicación y continuidad para agentes que operan fuera de Notion, especialmente Emisarios G-PRO y sus apoyos ChatGPT.

### Alcance inicial

- Normas comunes para Emisarios G-PRO.
- Reglas específicas de ASDA.
- Contrato de coordinación de continuidad de ASDA.
- Continuidad entre fases mediante GitHub, Docs y Notion.
- Historial de cambios y versión publicada.

## Relación con Notion, DDH y PCA/IA

- **Notion** conserva la gobernanza interna, ER, DDH, LOG canónicos y minutas cuando PCA/IA lo requiera.
- **GitHub** es el canal versionado de publicación de normas y el carril **GitHub -> ASDA (G-PRO)**.
- **Google Docs** contiene el carril de respuesta **ASDA (G-PRO) -> Notion** mediante un Doc espejo de una nota Notion.
- **PCA/IA** transfiere/conciliará el contenido de ese Doc hacia Notion.
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
- `delegados/ASDA-DELEGADO.md` — ruta histórica del contrato; su contenido documenta la clase especial de continuidad.
- `plantillas/PLANTILLA_ASDA_CONTINUIDAD_CON_DELEGADO_v2.2-CANDIDATA.md` — plantilla candidata.
- `CHANGELOG.md` — historial de cambios.
- `VERSION` — versión publicada.

## Excepción de nomenclatura — continuidad de Emisarios G-PRO

Los agentes ChatGPT que operan como continuidad de un Emisario G-PRO **no llevan el término “Delegado” en su nombre o firma**. Esta omisión es intencional y distingue esta clase especial de los Delegados ChatGPT ordinarios.

Caso ASDA:

- N+1: `📐 E3 ASDA (G-PRO)`
- firma desde la activación: `📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)`

La ruta de archivo `delegados/ASDA-DELEGADO.md` se conserva por trazabilidad histórica del diseño v2.2; no define la firma literal.

## Arquitectura direccional ASDA

### GitHub -> ASDA (G-PRO)

Buzón permanente:

https://github.com/by-iPV/gb-agent-governance/issues/1

- Escribe: `📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)`.
- Lee: `📐 E3 ASDA (G-PRO)`, al recibir π o cuando su flujo lo requiera.
- ASDA no responde por este carril.

### ASDA (G-PRO) -> Notion

- ASDA escribe en el Google Doc espejo.
- PCA/IA transfiere/conciliará hacia la nota espejo Notion.
- `📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)` lee la respuesta en Notion.

Nota Notion:
https://app.notion.com/p/41c42155482181d9820de441c4f936d2

Doc espejo:
https://docs.google.com/document/d/1cXWqqRy8vgkASRX9laXYRPfHgxwQCEym6KnukPAmMi8/edit

Los dos carriles son unidireccionales y complementarios; no forman un chat bidireccional en una sola plataforma.

## FIN DE FASE

- ASDA no delega ni transfiere sus propios FIN.
- `📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)` emite sus propios FIN cuando su fase y fuente canónica lo requieran.
- No duplicar un FIN como señal ejecutable en otro carril.
- Cerrar una Issue no equivale automáticamente a FIN, gate, DDH, ADELANTE o cierre PCA/IA.

## Seguridad y trazabilidad

- No publicar secretos, tokens ni credenciales.
- No publicar PII.
- No inferir autorizaciones.
- Conservar historial y versiones.
- Mantener referencias canónicas y siguiente acción.

## Gobierno de cambios

Un commit por sí solo no crea autorización HITL ni modifica automáticamente las reglas internas. Todo cambio normativo debe conservar referencia a su fuente, estado y decisión correspondiente.
