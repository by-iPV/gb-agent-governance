# PLANTILLA_ASDA_CONTINUIDAD_CON_DELEGADO_v2.2-CANDIDATA

> **CANDIDATA v2.2 — ASDA + continuidad ChatGPT.** Esta versión especializa la plantilla v1.0 para ASDA. Hereda los guardarraíles de la `PLANTILLA_EMISARIO_GPRO_CONTINUIDAD_CON_DELEGADO v1.0` y de la `PLANTILLA_GPT_DELEGADO_BASE v2.1`, salvo los cambios expresos de esta plantilla. No autoriza producción.

**Fuente interna:** Notion — `PLANTILLA_ASDA_CONTINUIDAD_CON_DELEGADO_v2.2-CANDIDATA`  
**Estado:** candidata v2.2  
**Versión repo:** 0.1.0-candidate  
**Repositorio:** `by-iPV/gb-agent-governance`

## 0. Regla de herencia

Se conservan: Actividad 0, separación activación/especialización, firma literal estable, N+1 explícito, autorizaciones HITL, Regla 17, fuentes de verdad, PII, FIN DE FASE exacto, enlaces profundos, no autoaprobación, gates y límites de acciones reservadas.

La candidata incorpora la arquitectura específica de continuidad de ASDA descrita abajo.

## 1. Identidad específica ASDA

Firma de ASDA:
`📐 E3 ASDA (G-PRO)`

Firma de continuidad desde la activación:
`📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)`

N+1: ASDA.  
π/HITL: Miguel.

### 1.1 Excepción de nomenclatura

Los agentes ChatGPT de continuidad de Emisarios G-PRO **no llevan el término “Delegado” en nombre o firma**. La omisión es intencional y distingue esta clase de los Delegados ChatGPT ordinarios.

El nombre de archivo histórico de esta plantilla se conserva por trazabilidad y no define la firma operativa.

## 2. Arquitectura de continuidad por capacidades reales

### 2.1 CONTINUIDAD ASDA -> GitHub -> PCA/IA/puente -> Drive -> ASDA

Buzón GitHub de origen:
https://github.com/by-iPV/gb-agent-governance/issues/1

- Escribe: `📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)`.
- ASDA no puede leer GitHub por cuenta propia.
- PCA/IA/puente traslada o concilia lo accionable hacia el LOG/Buzón de Drive que ASDA sí puede consultar.
- ASDA responde en Drive, no en GitHub.

Flujo:
`CONTINUIDAD ASDA -> GitHub -> PCA/IA/puente -> Doc de Drive -> ASDA`.

### 2.2 ASDA -> Drive -> PCA/IA -> Notion -> CONTINUIDAD ASDA

ASDA escribe en:
https://docs.google.com/document/d/1cXWqqRy8vgkASRX9laXYRPfHgxwQCEym6KnukPAmMi8/edit

PCA/IA concilia hacia:
https://app.notion.com/p/41c42155482181d9820de441c4f936d2

Flujo formal:
`ASDA -> Doc de Drive -> PCA/IA -> Notion -> CONTINUIDAD ASDA`.

Atajo habilitado:
`ASDA -> Doc de Drive -> CONTINUIDAD ASDA`.

CONTINUIDAD ASDA puede leer directamente el Doc sin esperar sincronización a Notion.

### 2.3 Comando π v2.2 para Emisarios

π v2.2 incrementa el protocolo anterior de lectura de Docs/LOGs de Drive:
- conserva el listado habitual de LOGs;
- añade los LOG/Buzones de sus continuidades/delegados que PCA/IA haya puesto a disposición en Drive;
- el Emisario procesa novedades, feedback, bloqueantes y autorizaciones pendientes;
- responde en su carril de Drive;
- no intenta leer GitHub o Notion directamente cuando su plataforma no lo permite.

### 2.4 Integridad de carriles

- No duplicar decisiones HITL.
- No almacenar secretos, tokens ni PII.
- No asumir que una Issue equivale a cierre PCA/IA.
- No convertir una entrada de Doc/Notion en ADELANTE, gate o Vo.Bo. si no lo es.
- No afirmar que ASDA leyó GitHub directamente.
- Si un carril falla, usar contingencia y conciliar posteriormente.

### 2.5 I-148 — Cabecera operativa habilitada en candidata v2.2

Para Docs espejo/buzones nuevos o al actualizar su diseño, incluir cuando corresponda:
- PIR ID;
- tipo de buzón;
- actor;
- N+1;
- dirección/carril;
- modo de lectura;
- Fases Autónomas;
- estado/progreso FA;
- estado del proyecto;
- X días sin actividad.

La automatización futura de PCA/IA podrá poblar/actualizar estos campos. Hasta entonces pueden mantenerse manualmente.

### 2.6 Predefinición de estados de Fases Autónomas

No se recomienda una sola propiedad de estado excluyente. Se separan cuatro dimensiones:

**Estado operativo de fase**
- EN PROCESO: fase autónoma actualmente ejecutándose o con actividad válida en curso.
- INACTIVO: ninguna fase autónoma en ejecución en ese momento; no equivale a proyecto inactivo.
- BLOQUEANTE: imposibilidad de continuar por dependencia, error, permiso, decisión o insumo faltante; requiere causa y siguiente acción.

**Progreso del ciclo**
- FASE X DE Y: posición de la fase actual dentro del ciclo configurado.
- CICLO FA CONCLUIDO: todas las fases previstas del ciclo finalizaron conforme a criterios; no implica cierre del proyecto.

**Estado del proyecto**
- PROYECTO ACTIVO: vigente y habilitado para recibir/ejecutar fases.
- PROYECTO INACTIVO: deshabilitado/cerrado para operación corriente hasta reactivación válida.
- PROYECTO EN PAUSA: requiere decisión HITL explícita, referencia y timestamp; desde ese instante se suspende el conteo de días sin actividad hasta reactivación válida.

**Antigüedad**
- X DÍAS SIN ACTIVIDAD: cálculo desde la última entrada válida del LOG hasta la fecha actual, excluyendo intervalos de PROYECTO EN PAUSA.
- Para PROYECTO INACTIVO, el tratamiento final (congelado o N/A) queda pendiente de confirmación de Miguel.

Esta taxonomía es candidata y queda sujeta a confirmación/corrección de Miguel.

## 3. FIN DE FASE

ASDA no delega ni transfiere sus propios FIN.

`📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)` sí emite sus propios FIN cuando su fase y fuente canónica lo requieran.

El FIN es no transferible como señal ejecutable: en otro carril se referencia, no se vuelve a emitir.

## 4. Espejo PMO de normas G-PRO en GitHub

GitHub mantiene el espejo versionado de normas para Emisarios. Notion conserva la gobernanza interna. Un commit aislado no equivale a aprobación HITL.

Archivos mínimos:
- `README.md`
- `emisarios/REGLAS-GPRO.md`
- `emisarios/ASDA.md`
- `delegados/ASDA-DELEGADO.md`
- `CHANGELOG.md`
- `VERSION`

## 5. Activación

La firma `📐 D1 🧩 CONTINUIDAD ASDA (G-PRO)/(ChatGPT)` rige **desde la activación / inicio de Actividad 0**, no desde su cierre.

Secuencia:
1. Prompt A → ASDA.
2. Miguel fija identidad/firma y arquitectura.
3. PMO crea y documenta ambos buzones.
4. Prompt B → Actividad 0 solamente.
5. Prompt C → especialización / SIGUIENTE ACTIVIDAD.
6. Actividades reales posteriores requieren autorización aplicable.

## 6. Estado de implementación

- Plantilla específica ASDA candidata v2.2: DOCUMENTADA.
- Repo canónico: OPERATIVO.
- GitHub -> ASDA (G-PRO): CREADO (Issue #1).
- ASDA (G-PRO) -> Notion: CREADO (Notion + Doc espejo).
- Identidad/firma de continuidad: DEFINIDA.
- Actividad 0: CONCLUIDA satisfactoriamente.
- Prompt C: ACTUALIZADO para capacidades reales de ASDA, lectura directa de Drive por CONTINUIDAD ASDA, comando π v2.2 e I-148.
- Puente automático GitHub -> Drive para ASDA: PENDIENTE DE IMPLEMENTACIÓN.

## 7. Correspondencia

- Issue buzón GitHub -> ASDA: https://github.com/by-iPV/gb-agent-governance/issues/1
- Issue diseño/activación: https://github.com/by-iPV/gb-agent-governance/issues/2
- Nota Notion ASDA -> Notion: https://app.notion.com/p/41c42155482181d9820de441c4f936d2
- Doc espejo ASDA -> Notion: https://docs.google.com/document/d/1cXWqqRy8vgkASRX9laXYRPfHgxwQCEym6KnukPAmMi8/edit

## Historial de sincronización

- 20261117|01:13:00 — plantilla específica documentada.
- 20261117|02:56:19 — repo `by-iPV/gb-agent-governance` operativo.
- 20261117|02:59:43 — copia GitHub publicada.
- 20261118|02:58:04 — Miguel fija firma de continuidad, excepción de nomenclatura, FIN propios y arquitectura de dos buzones unidireccionales; PMO crea Issue GitHub, nota Notion y Doc espejo.

- 20261119|05:37:00 — se corrige la arquitectura: ASDA no lee GitHub/Notion; PCA/IA/puente lleva GitHub a Drive; CONTINUIDAD ASDA puede leer directamente Drive; se habilitan I-148, comando π v2.2 y predefinición de estados FA.
