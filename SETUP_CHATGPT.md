# Configuración de ChatGPT — Deep Learning

Este repositorio no se sincroniza automáticamente con un Proyecto de ChatGPT. La configuración inicial y los cambios posteriores se aplican manualmente.

## Preparación inicial

1. Crea un Proyecto independiente llamado **SETS — Deep Learning**.
2. Copia el contenido de `CHATGPT_PROJECT_INSTRUCTIONS.md` en las instrucciones del Proyecto.
3. Sube, como mínimo, `PROJECT_CONFIG.yaml`, `PROJECT_RULES.md`, `learning/CURRICULUM.md`, `learning/CASEBOOK.md`, `learning/LEARNING_PATHS.md`, `learning/REFERENCES.md`, `state/LEARNING_STATE.md`, `state/EVIDENCE_LOG.md` y `state/README.md`.
4. Añade `sets-framework/core/PROJECT_INSTRUCTIONS.md`, `sets-framework/core/CONCEPTUAL_ENGINE.md`, `sets-framework/core/ASSESSMENT_ENGINE.md` y `sets-framework/core/SESSION_HANDOFF.md` desde el repositorio `sets-framework` como archivos de referencia si deseas utilizar el marco completo.
5. Inicia con `/start` o pide directamente `/learn <tema>`.

## Continuidad manual

- Al cerrar una sesión, revisa los artefactos que produzca `/close`.
- Verifica que el estado y las evidencias correspondan a trabajo real antes de actualizar los archivos locales.
- Si actualizas las instrucciones o los archivos del Proyecto, hazlo por separado; un commit en GitHub no modifica por sí solo los archivos cargados en ChatGPT.
- Mantén `EVIDENCE_LOG.md` como historial append-only. No inventes sesiones, notas ni dominio.

## Archivos recomendados por propósito

- **Siempre activos:** configuración, reglas, currículo, casebook, rutas de aprendizaje e instrucciones.
- **Continuidad:** `state/LEARNING_STATE.md`, `state/EVIDENCE_LOG.md` y `state/LAST_HANDOFF.md` después de un cierre real.
- **Bajo demanda:** referencias, experimentos, retos de transferencia y documentos del framework que ayuden a la sesión.
