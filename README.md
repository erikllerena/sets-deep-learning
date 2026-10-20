# SETS — Deep Learning

**Programa:** v1.0.4 · **Framework:** SETS v1.4.1 · **Namespace:** `DL00–DL14`

Comprender en profundidad cómo las redes neuronales representan funciones, aprenden parámetros mediante optimización, generalizan y dan lugar a arquitecturas modernas, con suficiente base matemática para explicar mecanismos y fallos.

## Pregunta central

> ¿Cómo aprenden las redes neuronales representaciones útiles y qué mecanismos determinan su capacidad, estabilidad y límites?

## Qué cubre

Redes neuronales; perceptrones y MLP; funciones de activación y pérdida; cálculo diferencial necesario; gradientes y backpropagation; optimización; inicialización; normalización; regularización; CNN; modelos secuenciales; atención y Transformers; representaciones aprendidas; arquitecturas generativas; eficiencia, entrenamiento y reproducibilidad.

## Qué no intenta cubrir

Se centra en los mecanismos y arquitecturas de redes neuronales. Los objetivos de generación, familias de productos generativos, prompting, RAG y sistemas multimodales se estudian desde su aplicación en Generative AI. Los algoritmos clásicos y evaluación estadística general pertenecen a Machine Learning; aquí se cubren cuando son necesarios para explicar redes neuronales.

## Principios de aprendizaje

- Conceptos y mecanismos antes que recetas o herramientas.
- Currículo abierto: los módulos priorizan competencias; no limitan los temas que pueden estudiarse.
- Casos ilustrativos, no exclusivos. El caso conductor es opcional.
- Profundidad adaptable: fundamento, profundización y especialización son alcances, no etapas obligatorias.
- Neutralidad tecnológica: ningún lenguaje, biblioteca, proveedor o stack es requisito universal.
- Práctica opcional por defecto; explicar y razonar también producen evidencia.
- Evidencia honesta: no se infiere dominio por lectura pasiva, familiaridad o una sola respuesta.
- Autonomía: este programa conserva su propio currículo y estado; no importa progreso de otros SETS.

## Estructura

- `PROJECT_CONFIG.yaml`: configuración del programa.
- `PROJECT_RULES.md`: reglas específicas y límites disciplinares.
- `CHATGPT_PROJECT_INSTRUCTIONS.md`: instrucciones para el Proyecto de ChatGPT.
- `learning/CURRICULUM.md`: mapa de competencias abierto.
- `learning/CASEBOOK.md`: casos ilustrativos.
- `learning/LEARNING_PATHS.md`: rutas no obligatorias.
- `practice/EXPERIMENTS.md`: ideas de experimentación optativas.
- `practice/TRANSFER_CHALLENGES.md`: retos opcionales para transferir principios.
- `labs/LAB_GUIDE.md`: convenciones para laboratorios sin inventar ejecuciones o resultados.
- `decisions/PROGRAM_DECISIONS_GUIDE.md`: registro de cambios importantes de diseño/alcance del propio programa (no actividad cotidiana del estudiante).
- `state/`: estado y evidencias del aprendizaje; incluye `state/CONCEPT_MAP.md`, recomendado como fuente de relaciones conceptuales desde el inicio (opcional y sin progreso acreditado).
- `docs/ACCEPTANCE_CHECKS.md`: pruebas manuales del comportamiento del tutor (no evaluación del estudiante).

**Uso de fuentes:** `practice/` y `labs/LAB_GUIDE.md` son recomendados desde el inicio, pero las actividades son optativas. `decisions/` y `docs/` se consultan al mantener o auditar el programa, no como material obligatorio de cada clase. Véase `SETUP_CHATGPT.md`.

## Cómo empezar

1. Lee `SETUP_CHATGPT.md`.
2. Crea un Proyecto independiente en ChatGPT para esta especialidad.
3. Copia el contenido de `CHATGPT_PROJECT_INSTRUCTIONS.md` en sus instrucciones y carga los archivos pertinentes.
4. Inicia con `/start` o comienza directamente con `/learn <tema>`.
5. Al cerrar una sesión, utiliza `/close` y revisa los artefactos de continuidad antes de actualizar tu copia local o GitHub.

> GitHub y los archivos de un Proyecto de ChatGPT no se sincronizan automáticamente por defecto. Mantén cualquier actualización manual y verifica el contenido antes de reemplazar archivos.

## Versionado

Versión actual del programa: `v1.0.4` (base inicial `v1.0.0`). Se alinea con SETS Framework `v1.4.1`, sin modificarlo.
