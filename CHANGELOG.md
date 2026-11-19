# Changelog

## 0.1.0-candidate — 2026-11-17

### Added

- Inicialización del repositorio de gobernanza GB.
- Normas comunes para Emisarios G-PRO.
- Reglas específicas de continuidad de ASDA.
- Contrato ASDA ↔ continuidad ChatGPT.
- Regla de plataforma: no exigir a Emisarios documentar directamente en Notion cuando su canal aplicable sea otro.
- FIN DE FASE no transferible entre fuentes.
- Separación entre GitHub, Notion, Docs y chat.

### Updated — 2026-11-18

Decisión directa de Miguel:

- Firma ASDA: `📐 E3 ASDA (G-PRO)`.
- Firma de continuidad desde Actividad 0: `📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)`.
- Excepción: los agentes ChatGPT de continuidad de Emisarios G-PRO no llevan “Delegado” en nombre o firma.
- Arquitectura sustituida por dos carriles unidireccionales:
  - **GitHub -> ASDA (G-PRO)**: Issue #1; escribe CONTINUIDAD ASDA y ASDA lee al recibir π.
  - **ASDA (G-PRO) -> Notion**: ASDA escribe en Google Doc espejo; PCA/IA concilia hacia Notion; CONTINUIDAD ASDA lee en Notion.
- ASDA conserva sus propios FIN; CONTINUIDAD ASDA emite sus FIN propios cuando correspondan.
- Firma vigente desde la activación, no desde el cierre de Actividad 0.

### Source basis

- PLANTILLA_GPT_DELEGADO_BASE v2.1.
- MINUTA PMO — Ideas, propuestas y casillas de revisión HITL — 20261112.
- IDEA TRANSVERSAL — Delegado ASDA, interoperabilidad GitHub y continuidad PCA-IA — 20261112.
- PLANTILLA_EMISARIO_GPRO_CONTINUIDAD_CON_DELEGADO v1.0.
- PLANTILLA_ASDA_CONTINUIDAD_CON_DELEGADO_v2.2-CANDIDATA.
- Decisión directa de Miguel del 2026-11-18.

### Status

Candidata v2.2. No constituye autorización de producción.

## Updated — 2026-11-19

Decisión directa de Miguel:

- Se corrige la capacidad real de ASDA/G-PRO: ASDA no puede leer GitHub por cuenta propia ni Notion.
- Flujo hacia ASDA: `CONTINUIDAD ASDA -> GitHub -> PCA/IA/puente -> Doc de Drive -> ASDA`.
- Flujo de retorno: `ASDA -> Doc de Drive -> PCA/IA -> Notion -> CONTINUIDAD ASDA`.
- CONTINUIDAD ASDA puede leer directamente el Doc de Drive sin esperar la conciliación a Notion.
- Prompt C actualizado después de Actividad 0 concluida.
- π v2.2 para Emisarios conserva los LOGs habituales de Drive y añade lectura de LOG/Buzón de su continuidad/delegado cuando esté materializado en Drive.
- I-148 queda habilitada en la candidata v2.2 como cabecera operativa de Docs espejo/buzones.
- Se incorpora predefinición candidata de estados FA: EN PROCESO, INACTIVO, BLOQUEANTE, FASE X DE Y, CICLO FA CONCLUIDO, PROYECTO ACTIVO, PROYECTO INACTIVO, PROYECTO EN PAUSA y X DÍAS SIN ACTIVIDAD.

