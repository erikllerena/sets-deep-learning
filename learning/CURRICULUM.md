# Mapa de competencias — Deep Learning

**Programa v1.0.0 · SETS Framework v1.4.1 · Namespace `DL00–DL14`**

Comprender en profundidad cómo las redes neuronales representan funciones, aprenden parámetros mediante optimización, generalizan y dan lugar a arquitecturas modernas, con suficiente base matemática para explicar mecanismos y fallos.

Este mapa define competencias prioritarias, no agota todos los temas que pueden estudiarse. Enseña preguntas relevantes fuera del índice y relaciónalas con competencias existentes cuando ayude; solo propón un módulo nuevo si el tema es recurrente o estratégicamente central. Fundamento, profundización y especialización son alcances adaptativos, no fases obligatorias.

## Competencias observables

| ID | Competencia | Capacidad observable | Pregunta conceptual central | Evidencia posible |
| --- | --- | --- | --- | --- |
| DL00 | Diagnóstico y mapa de prerrequisitos | Identificar intuiciones y brechas relevantes en álgebra, cálculo, probabilidad y ML sin imponer un curso matemático previo completo. | ¿Qué fundamento necesitamos ahora para explicar el mecanismo? | Mapa adaptativo de conceptos y prerrequisitos. |
| DL01 | De modelos lineales a redes neuronales | Relacionar combinación de características, composición de funciones y representaciones aprendidas. | ¿Qué limitación de un modelo simple puede resolver una red? | Explicación de una función que requiere composición no lineal. |
| DL02 | Perceptrón, MLP y flujo hacia delante | Rastrear tensores, pesos, sesgos, capas y dimensiones en una red pequeña. | ¿Cómo transforma una entrada una red neuronal? | Traza de forward pass con dimensiones y supuestos. |
| DL03 | Activaciones, pérdidas y objetivos | Explicar cómo activaciones y funciones de pérdida condicionan señales de aprendizaje. | ¿Qué señal le dice al modelo qué resultado mejorar? | Comparación de pérdidas según tarea y distribución. |
| DL04 | Gradientes y backpropagation | Derivar la regla de la cadena y entender cómo se distribuye el gradiente por la red. | ¿Cómo sabe cada parámetro en qué dirección cambiar? | Cálculo o traza de gradientes en una red pequeña. |
| DL05 | Optimizadores y dinámica del entrenamiento | Comparar SGD, momentum, Adam y decisiones de tasa de aprendizaje con evidencia. | ¿Cómo afectan las actualizaciones al progreso y estabilidad? | Análisis de curvas de entrenamiento bajo cambios controlados. |
| DL06 | Inicialización, normalización y estabilidad | Comprender escalas de activación, gradientes que desaparecen/explotan y técnicas de estabilización. | ¿Por qué una red puede ser difícil de entrenar aunque la arquitectura parezca correcta? | Diagnóstico de inestabilidad y propuesta de intervención. |
| DL07 | Generalización y regularización neuronal | Analizar capacidad, datos, weight decay, dropout, augmentation y early stopping. | ¿Cómo se evita memorizar el conjunto de entrenamiento? | Experimento controlado de generalización. |
| DL08 | Redes convolucionales | Comprender localidad, filtros, compartición de pesos, stride, padding y jerarquías espaciales. | ¿Qué estructura de los datos aprovecha una CNN? | Trazado de dimensiones y análisis de inductive bias. |
| DL09 | Modelos secuenciales | Entender RNN/LSTM y sus fortalezas y límites frente a alternativas modernas. | ¿Qué dificultades aparecen cuando la información depende del orden y la distancia temporal? | Comparación de mecanismos para secuencias. |
| DL10 | Atención y Transformers | Explicar queries, keys, values, atención, positional information y bloques Transformer. | ¿Cómo selecciona una red información contextual entre elementos? | Traza conceptual y dimensional de un bloque de atención. |
| DL11 | Representaciones y aprendizaje autosupervisado | Estudiar embeddings, objetivos contrastivos y representaciones aprendidas. | ¿Qué propiedades de los datos quedan codificadas en el espacio aprendido? | Evaluación de una representación y sus límites. |
| DL12 | Arquitecturas generativas neuronales | Comprender VAE, GAN, modelos de difusión y otros enfoques como familias de mecanismos. | ¿Cómo puede un modelo aprender una distribución y producir nuevas muestras? | Comparación de objetivos, mecanismos y modos de fallo. |
| DL13 | Escala, eficiencia y reproducibilidad | Analizar lotes, memoria, precisión numérica, paralelismo, semillas y diseño de experimentos. | ¿Qué limita el entrenamiento y cómo separamos mejora real de ruido experimental? | Protocolo reproducible y análisis de recursos. |
| DL14 | Capstone de Deep Learning | Integrar arquitectura, entrenamiento, evaluación, ablations y límites del modelo. | ¿Qué evidencia justifica esta arquitectura y qué queda sin demostrar? | Informe experimental con decisiones y resultados verificables. |

## Cómo se aprende

Selecciona las lentes conceptuales según la pregunta y las brechas observadas: origen/problema, mecanismo causal, supuestos y límites, alternativas/trade-offs y transferencia. No conviertas las lentes en cinco pasos obligatorios ni en una escala de dominio.

## Formas de evidencia

La evidencia puede ser una explicación propia, una predicción, un cálculo, un diagrama, una traza, una comparación, un experimento, un análisis de error o una implementación. Una respuesta del tutor, una lectura o una salida copiada no demuestra por sí sola el desempeño del estudiante.

## Criterio de comprensión profunda

Se busca que el estudiante pueda explicar el problema y el mecanismo, declarar supuestos, anticipar consecuencias o fallos, reconocer límites y razonar sobre alternativas. El dominio se decide con las reglas de `sets-framework/core/ASSESSMENT_ENGINE.md`, no por contar módulos completados.
