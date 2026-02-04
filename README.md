Proyecto final: Del archivo al insight - Asistente de datos para pequeños emprendedores
Resumen

Este proyecto presenta una Prueba de Concepto (POC) de un asistente de análisis de datos diseñado para emprendedores en Argentina. El sistema utiliza modelos de lenguaje para transformar archivos CSV o Excel en información útil mediante consultas en lenguaje natural y visualizaciones automáticas.
1. Introducción
Presentación del problema

En Argentina, muchos emprendedores registran sus ventas en planillas simples pero carecen de conocimientos técnicos en programación o análisis avanzado. Esto genera una dependencia de especialistas y dificulta la toma de decisiones basada en evidencia, limitando el crecimiento de los negocios.
Propuesta de solución

Se propone un asistente basado en Prompt Engineering que permite realizar tres tareas principales:

    Consultas de texto: El usuario pregunta en español y recibe una respuesta resumida y clara.

    Gráficos técnicos: Generación de visualizaciones precisas (barras, líneas) mediante código Python.

    Infografías estéticas: Creación de piezas visuales conceptuales para facilitar la comunicación de resultados.

2. Objetivos

    Democratizar el acceso al análisis de datos para usuarios sin formación técnica.

    Automatizar la generación de reportes visuales a partir de archivos planos.

    Optimizar la interacción con modelos de IA mediante técnicas de Fast Prompting.

3. Justificación de Viabilidad

El proyecto es viable porque utiliza datasets simples de pocos registros, lo que asegura un bajo consumo de tokens y costos reducidos. Se utiliza GPT-4 (y sus versiones mini) por su capacidad probada para interpretar lenguaje natural y devolver resultados consistentes.
4. Metodología y Tecnologías
Herramientas utilizadas

    Modelos: GPT-4o-mini para texto y código; DALL-E 3 para imágenes.

    Lenguaje: Python, utilizando librerías como Pandas para datos y Matplotlib para gráficos.

    Entorno: Jupyter Notebook (Google Colab).

Técnicas de Prompting

    System Prompting: Definición de un rol de analista senior para guiar el tono y precisión de las respuestas.

    In-Context Learning: Inyección de la estructura del dataset directamente en el prompt para evitar alucinaciones.

    Dynamic Code Execution: El modelo genera código que se ejecuta en el entorno para garantizar la fidelidad de los datos.

5. Resultados y Conclusiones

La implementación demuestra que es posible obtener respuestas de negocio accionables y gráficos precisos de forma automática. Se concluye que el Prompt Engineering funciona como un puente efectivo entre el lenguaje natural y el análisis técnico, cumpliendo los objetivos planteados.
6. Referencias

    Documentación oficial de OpenAI.

    Consignas del curso Coderhouse: "IA: Entretejiendo Imaginación y Algoritmos".
