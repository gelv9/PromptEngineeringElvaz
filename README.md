Proyecto – Preentrega Prompt Engineering

Este proyecto es mi preentrega para la materia IA – Generación de Prompts.
La idea principal es resolver un problema común de los pequeños emprendedores en Argentina:
muchos registran sus datos en planillas simples (CSV o Excel) pero no saben programar ni usar SQL para analizarlos.

Objetivo

Construí un flujo simple que permita:

Texto → Texto

El usuario puede hacer preguntas en lenguaje natural sobre sus datos.

El modelo devuelve un insight breve y accionable.

Texto → Código → Imagen

A partir de la misma información, el modelo genera código en Python (Matplotlib).

Ese código se ejecuta y devuelve un gráfico con los resultados.

Texto → Imagen

El gráfico generado se utiliza como base para producir una infografía decorativa, más estética y fácil de comunicar.

Para esta parte usé el modelo gpt-image-1. Requiere tener la organización de OpenAI verificada, por lo que puede dar error 403 si no está habilitado.

Contenido

notebook.ipynb → Notebook en Google Colab con todo el flujo.

dataset_prueba.csv → Dataset simple de ejemplo para correr las pruebas.
