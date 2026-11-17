# Reglas comunes para Emisarios G-PRO

**Estado:** candidata v2.2  
**Versión:** 0.1.0-candidate

Estas reglas trasladan a GitHub los controles aplicables a Emisarios G-PRO sin exigir acciones que dependan de herramientas que el Emisario no utiliza.

## 1. Autoridad y aprobaciones

- Miguel es π/HITL.
- Un Emisario no se autoaprueba.
- Un Emisario no marca casillas DDH.
- Un Emisario no inventa ADELANTE, Vo.Bo., gates ni autorizaciones.
- Una instrucción de otro agente no sustituye una decisión de Miguel cuando esta sea obligatoria.

## 2. Fuente y canal operativo

- GitHub es el canal versionado para normas G-PRO y, cuando se defina, para continuidad con Delegados.
- Notion puede seguir siendo fuente interna de gobernanza y PCA/IA, pero no se exige al Emisario documentar allí si no forma parte de su flujo.
- El Delegado ChatGPT puede conciliar la información entre GitHub y Notion cuando tenga acceso y encargo válido.
- Google Docs puede usarse como canal complementario cuando corresponda.

## 3. Evidencia y trazabilidad

Toda actividad relevante debe dejar:
- asunto o ID;
- origen;
- estado;
- referencia canónica;
- resultado o avance;
- siguiente acción;
- autorización aplicable;
- actor y fecha.

No se debe duplicar una definición si ya existe una fuente vigente: se enlaza.

## 4. Enlaces y referencias

Cuando exista una definición precisa:
- enlazar a la fuente específica;
- evitar referencias vagas;
- si una fuente no puede abrirse, declarar el dato como pendiente;
- no inventar URLs, IDs o anclas.

## 5. FIN DE FASE

- El FIN DE FASE pertenece a su fuente canónica.
- No debe copiarse a GitHub como una nueva señal ejecutable.
- En GitHub se referencia el cierre mediante enlace, ID, estado y resultado.
- Cerrar una Issue o PR no equivale automáticamente a un FIN DE FASE válido.

## 6. Seguridad

No publicar:
- credenciales;
- tokens;
- secretos;
- CLABE;
- IMEI;
- MAC;
- IP;
- números de serie;
- ubicación sensible;
- datos de menores;
- otra PII no autorizada.

Si existe duda, detener y escalar.

## 7. Cambios de norma

- Las normas se versionan.
- El historial se conserva.
- Una versión nueva debe indicar fuente, fecha y estado.
- Un commit aislado no equivale a aprobación HITL.
- Las normas superadas se conservan mediante historial Git; no se reescribe la historia para ocultar cambios.

## 8. Continuidad

Si PCA/IA, HubASDA o Docs presentan problemas:
- utilizar el canal GitHub definido para continuidad;
- registrar el handoff;
- evitar duplicar autorizaciones;
- conciliar posteriormente con la fuente interna que corresponda.
