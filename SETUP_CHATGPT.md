# Configuración de ChatGPT — Deep Learning | Programa v1.0.4

Los repositorios GitHub y las fuentes de un Proyecto de ChatGPT **no se sincronizan automáticamente**. Cada especialidad usa su propio Proyecto, archivos de estado y evidencias. **No es necesario subir todos los archivos del repositorio:** tienen propósitos distintos.

### Atención: las fuentes se suben como archivos individuales

En ChatGPT, **no se carga la estructura de carpetas del repositorio como contexto fiable**. El tutor debe poder identificar cada fuente por el **nombre real del archivo**, no por la ruta de GitHub. Por eso renombramos las tres antiguas guías `README.md` a nombres únicos: `STATE_ARTIFACTS_GUIDE.md` (estado), `LAB_GUIDE.md` (laboratorios) y `PROGRAM_DECISIONS_GUIDE.md` (decisiones de diseño del programa). Al elegir archivos en tu computadora usa las rutas que aparecen abajo; una vez subidos, **sus nombres visibles deben coincidir exactamente**.

Los archivos raíz `README.md` de GitHub (programa o framework) no son fuentes necesarias. Si un documento futuro repite el nombre de otro archivo cargado, hay que desambiguarlo antes de subirlo. No confíes en que ChatGPT podrá recuperar su carpeta original.

## 1. Crear el Proyecto y sus instrucciones activas

1. Crea un Proyecto independiente llamado **SETS — Deep Learning**.
2. Pega **únicamente** el contenido de `CHATGPT_PROJECT_INSTRUCTIONS.md` en las **instrucciones del Proyecto**. Evita apilar versiones antiguas o pegar los motores completos como instrucciones activas.

## 2. Fuentes esenciales de este programa

Carga estos archivos del repositorio **sets-deep-learning** como **fuentes del Proyecto**:

- `PROJECT_CONFIG.yaml` — identidad, alcance, preferencias y configuración.
- `PROJECT_RULES.md` — reglas del dominio y fronteras con otras especialidades.
- `learning/CURRICULUM.md` — competencias y mapa abierto, no temario cerrado.
- `learning/CASEBOOK.md` — casos ilustrativos, no obligatorios.
- `learning/LEARNING_PATHS.md` — rutas sugeridas, no prerrequisitos rígidos.
- `learning/REFERENCES.md` — referencias de aprendizaje.
- `state/LEARNING_STATE.md` — estado actual del estudiante.
- `state/EVIDENCE_LOG.md` — evidencias reales; historial append-only.
- `state/STATE_ARTIFACTS_GUIDE.md` — reglas de los artefactos de continuidad.

**Fuentes recomendadas desde el inicio (no obligatorias):**

- `state/CONCEPT_MAP.md` — relaciones conceptuales justificadas, sin duplicar currículo ni acreditar dominio.
- `practice/EXPERIMENTS.md` — ideas de experimentos; consúltalas cuando un experimento ayude a verificar un mecanismo o hipótesis.
- `practice/TRANSFER_CHALLENGES.md` — retos para comprobar transferencia a situaciones nuevas, sin convertir cada lección en un examen.
- `labs/LAB_GUIDE.md` — convenciones de laboratorios: optativos, pueden ser conceptuales y solo se archivan resultados reales.

Si no cargas alguna fuente recomendada, el tutor puede continuar. En ese caso, no debe fingir haberla consultado.

## 3. Fuentes esenciales del SETS Framework v1.4.1

Carga desde el repositorio **`sets-framework` v1.4.1** los archivos siguientes como **fuentes**, no como instrucciones activas:

- `core/PROJECT_INSTRUCTIONS.md` — reglas pedagógicas comunes de referencia.
- `core/CONCEPTUAL_ENGINE.md` — comprensión y explicación causal.
- `core/INTERACTION_ENGINE.md` — interacción y diálogo adaptativo.
- `core/DECISION_ENGINE.md` — criterios, alternativas y decisiones.
- `core/PRACTICE_ENGINE.md` — práctica deliberada y transferencia.
- `core/ASSESSMENT_ENGINE.md` — evaluación y evidencia.
- `core/SESSION_HANDOFF.md` — cierre y continuidad.
- `templates/LAST_HANDOFF.template.md` — formato del cierre.

**Recomendadas cuando aporten valor:** `templates/CONCEPT_MAP.template.md`, `templates/ADR_TEMPLATE.md`, `docs/REFERENCE_POLICY.md`, `docs/LEARNING_SCIENCE.md`, `docs/QUALITY_CHECKS.md` y `docs/COMMAND_REFERENCE.md`.

> El ZIP individual del programa no incluye el framework. Reutiliza el mismo framework para los cinco Proyectos; no crees cinco frameworks distintos.

## 4. ¿Para qué sirven las carpetas `decisions/`, `docs/`, `labs/` y `practice/`?

| Carpeta / archivos | Uso real | ¿Subir al Proyecto? |
|---|---|---|
| `practice/EXPERIMENTS.md` | Inspirar experimentos, con hipótesis, variables, observaciones y límites. | **Recomendado inicialmente**; usar solo si aporta a la sesión o el estudiante pide practicar. |
| `practice/TRANSFER_CHALLENGES.md` | Comprobar transferencia con un problema, restricción o contexto diferente. | **Recomendado inicialmente**, sin imponer retos automáticamente. |
| `labs/LAB_GUIDE.md` | Criterios para laboratorios optativos, con o sin código, y registro honesto. | **Recomendado inicialmente**; cargar informes concretos solo cuando existan y sean relevantes. |
| `decisions/PROGRAM_DECISIONS_GUIDE.md` | Convenciones para documentar cambios **pedagógicos o de alcance del programa**. No es un historial de decisiones técnicas del estudiante. | **Bajo demanda**, al revisar el diseño o reglas del SETS; los documentos de decisión reales solo si existen. |
| `docs/ACCEPTANCE_CHECKS.md` | Pruebas manuales para auditar que el tutor respeta las reglas y el alcance. | **Para sesiones de validación**; no hace falta cargarlo en clases ordinarias ni usarlo para calificar al estudiante. |

**Importante:** `decisions/` no sustituye al motor común `DECISION_ENGINE.md` ni a un ADR técnico que el estudiante decida realizar. `labs/` tampoco implica que haya prácticas completadas; por defecto contiene solo reglas, no resultados. `docs/ACCEPTANCE_CHECKS.md` describe pruebas pendientes de ejecución, no pruebas aprobadas.

## 5. Primera sesión y criterios de uso

- `/start` — diagnóstico breve, una pregunta por turno; luego enseñanza conceptual.
- `/learn <tema>` o `/deep <tema>` — enseña sin exigir laboratorio previo.
- `/lab <tema>` — elige/adapta un experimento pertinente, preferiblemente desde `practice/EXPERIMENTS.md` si está cargado; presenta objetivo, método, evidencia esperada y limitaciones. El usuario puede proponer uno nuevo.
- `/challenge` — propone un caso de transferencia si ayuda a comprobar comprensión, preferiblemente desde `practice/TRANSFER_CHALLENGES.md` si está cargado.
- `/close` — entrega `LAST_HANDOFF.md`, `LEARNING_STATE.md` íntegro actualizado y delta de `EVIDENCE_LOG.md`; no atribuyas resultados no observados.

El contenido de `practice/` es un banco de ideas, **no** un itinerario obligatorio ni una lista cerrada. Los laboratorios extensos requieren aceptación, salvo solicitud explícita del estudiante.

## 6. Cambios, verificación y continuidad

- Para **validar el tutor**, utiliza `docs/ACCEPTANCE_CHECKS.md` como lista de pruebas manuales; anota evidencia real, fecha y resultado. No mezcles esos checks con las evaluaciones del estudiante.
- Para **cambiar reglas, currículo o fronteras** de la especialidad, consulta `decisions/PROGRAM_DECISIONS_GUIDE.md` y documenta una decisión de programa cuando el cambio lo amerite.
- Para **documentar un laboratorio realmente realizado**, sigue `labs/LAB_GUIDE.md`; no inventes ejecución, métricas ni resultados. El estudiante revisa y decide qué guardar.
- En `/close`, revisa los artefactos propuestos antes de reemplazar los archivos del repositorio o las fuentes del Proyecto. `state/LAST_HANDOFF.md` solo existe después de un cierre real.
- Si actualizas `state/CONCEPT_MAP.md`, registra únicamente relaciones justificadas; sincroniza manualmente GitHub y las fuentes del Proyecto.
- Si reemplazas fuentes o instrucciones, elimina versiones duplicadas. Un commit de GitHub no actualiza ChatGPT por sí mismo.

## 7. Control de nombres al cargar fuentes

1. En **Fuentes del Proyecto**, verifica los nombres **individuales**, no las carpetas que existían en GitHub.
2. No debe haber dos archivos con el mismo nombre visible dentro de un Proyecto. Comprueba especialmente las antiguas guías `README.md`.
3. Carga `STATE_ARTIFACTS_GUIDE.md` y, si deseas prácticas, `LAB_GUIDE.md`; para cambios del programa usa `PROGRAM_DECISIONS_GUIDE.md` bajo demanda.
4. Los motores compartidos conservan nombres distintos (`INTERACTION_ENGINE.md`, `DECISION_ENGINE.md`, `PRACTICE_ENGINE.md`, etc.); solo se añade **un** programa especializado por Proyecto.
5. Si previamente subiste alguno de los antiguos `README.md`, elimínalo de Fuentes y sube la versión renombrada; no basta con actualizar el repositorio.
