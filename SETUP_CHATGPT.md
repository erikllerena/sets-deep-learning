# Configuración de ChatGPT — Deep Learning

Este repositorio no se sincroniza automáticamente con un Proyecto de ChatGPT. La configuración inicial y los cambios posteriores se aplican manualmente.

## Preparación inicial

1. Crea un Proyecto independiente llamado **SETS — Deep Learning**.
2. Copia el contenido de `CHATGPT_PROJECT_INSTRUCTIONS.md` en las instrucciones del Proyecto.
3. Sube, como mínimo, `PROJECT_CONFIG.yaml`, `PROJECT_RULES.md`, `learning/CURRICULUM.md`, `learning/CASEBOOK.md`, `learning/LEARNING_PATHS.md`, `learning/REFERENCES.md`, `state/LEARNING_STATE.md`, `state/EVIDENCE_LOG.md` y `state/README.md`.
4. **Recomendado desde el inicio:** añade `state/CONCEPT_MAP.md` a las fuentes del Proyecto. Su uso es opcional: si aún no lo subes, el tutor puede funcionar normalmente. El mapa sirve para conectar conceptos; no reemplaza al currículo, el estado ni las evidencias.
5. **Carga las fuentes esenciales del framework común**, tomadas de `sets-framework` **v1.4.1**, en este mismo Proyecto de ChatGPT. No son archivos exclusivos de esta especialidad ni requieren un framework distinto:

   **Esenciales — SETS Framework v1.4.1:**
   - `core/PROJECT_INSTRUCTIONS.md` — marco compartido como fuente (no lo pegues encima de las instrucciones activas del programa).
   - `core/CONCEPTUAL_ENGINE.md` — comprensión de conceptos y mecanismos.
   - `core/INTERACTION_ENGINE.md` — interacción didáctica y diálogo adaptativo.
   - `core/DECISION_ENGINE.md` — razonamiento sobre decisiones, criterios y alternativas.
   - `core/PRACTICE_ENGINE.md` — práctica deliberada, experimentos y transferencia.
   - `core/ASSESSMENT_ENGINE.md` — valoración de evidencias y competencias.
   - `core/SESSION_HANDOFF.md` — continuidad y cierre de sesiones.
   - `templates/LAST_HANDOFF.template.md` — formato del traspaso de sesión.

   **Recomendadas cuando aporten valor:**
   - `templates/CONCEPT_MAP.template.md` — plantilla general, distinta del mapa vivo de esta especialidad.
   - `templates/ADR_TEMPLATE.md` — registro de decisiones cuando realmente sea útil.
   - `docs/REFERENCE_POLICY.md` — uso de fuentes y referencias.
   - `docs/LEARNING_SCIENCE.md` — criterios pedagógicos del framework.
   - `docs/QUALITY_CHECKS.md` y `docs/COMMAND_REFERENCE.md` — controles y comandos disponibles.

   **Importante:** las **instrucciones activas** del Proyecto siguen siendo únicamente las de `CHATGPT_PROJECT_INSTRUCTIONS.md` de esta especialidad (paso 2). Los motores del framework se cargan como **fuentes del Proyecto**. Si ya tenías versiones anteriores de estas fuentes, sustitúyelas en lugar de conservar duplicados. Los ZIP individuales de IA no incluyen los archivos del framework: extráelos de tu repositorio `sets-framework` v1.4.1 o del paquete integral del ecosistema.
6. Inicia con `/start` o pide directamente `/learn <tema>`.

## Continuidad manual

- Al cerrar una sesión, revisa los artefactos que produzca `/close`.
- Verifica que el estado y las evidencias correspondan a trabajo real antes de actualizar los archivos locales.
- Si actualizas las instrucciones o los archivos del Proyecto, hazlo por separado; un commit en GitHub no modifica por sí solo los archivos cargados en ChatGPT.
- Mantén `EVIDENCE_LOG.md` como historial append-only. No inventes sesiones, notas ni dominio.
- Si aparecen relaciones conceptuales útiles, propón una actualización verificable de `state/CONCEPT_MAP.md`; el usuario revisa y reemplaza manualmente la copia del Proyecto y la del repositorio. No lo actualices por mera mención de un tema ni inventes conexiones o dominio.

## Archivos recomendados por propósito

- **Base del Proyecto:** configuración, reglas, currículo, casebook, rutas de aprendizaje e instrucciones.
- **Fuente recomendada desde el inicio (no obligatoria):** `state/CONCEPT_MAP.md` para consultar y construir conexiones justificadas entre conceptos.
- **Continuidad:** `state/LEARNING_STATE.md`, `state/EVIDENCE_LOG.md` y `state/LAST_HANDOFF.md` después de un cierre real.
- **Bajo demanda:** referencias, experimentos, retos de transferencia y documentos del framework que ayuden a la sesión.
