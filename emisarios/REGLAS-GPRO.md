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

- GitHub es canal versionado de normas G-PRO y puede ser fuente del lado ChatGPT/PCA-IA.
- Un Emisario G-PRO no debe ser instruido para leer GitHub o Notion directamente cuando su entorno no ofrezca esa capacidad autónoma.
- Google Drive/Docs es la interfaz operativa de lectura/escritura para el Emisario cuando así esté definido.
- PCA/IA/puente puede trasladar o conciliar información desde GitHub/Notion hacia un LOG/Buzón de Drive.
- La continuidad/delegado ChatGPT puede leer directamente Drive cuando tenga acceso real, sin esperar necesariamente la sincronización hacia Notion.
- Notion conserva gobernanza y trazabilidad interna cuando corresponda.

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

Si existen carriles entre plataformas:
- registrar el handoff en la fuente que el actor sí pueda usar;
- no asumir que el Emisario puede leer GitHub o Notion;
- usar PCA/IA/puente para materializar en Drive lo que el Emisario deba leer;
- evitar duplicar autorizaciones;
- conciliar posteriormente con la fuente interna que corresponda.

## 9. Comando π v2.2 — lectura de LOG/Buzón de continuidad

La operación π v2.2 incrementa el protocolo previo: no elimina el listado habitual de Docs/LOGs de Drive.

Cuando un Emisario reciba π:
1. revisa sus Docs/LOGs habituales de Drive;
2. revisa además los LOG/Buzones de sus continuidades/delegados que estén disponibles en Drive;
3. procesa novedades, feedback, bloqueantes, handoffs y solicitudes de autorización dirigidas al Emisario;
4. responde en el Doc/carril de Drive definido para ese actor;
5. no intenta leer GitHub o Notion directamente si su plataforma no lo permite;
6. no transforma por inferencia una entrada en ADELANTE, Vo.Bo., gate o FIN.

La lista exacta de Docs/LOGs que consulta cada Emisario sigue siendo específica de su rol/configuración.

## 10. Cabecera operativa de Docs espejo — I-148

La candidata v2.2 habilita como estándar documental la cabecera operativa mínima para nuevos Docs espejo/buzones o cuando se actualice su diseño:
- PIR ID;
- tipo de buzón;
- actor;
- N+1;
- dirección/carril;
- modo de lectura;
- Fases Autónomas;
- estado FA/progreso;
- estado del proyecto;
- X días sin actividad cuando aplique.

Mientras PCA/IA no automatice estas propiedades, pueden mantenerse manualmente por el actor autorizado.
