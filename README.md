# Bootcamp-PY-Examen_Fundamentos
Bootcamp - PY - Examen Fundamentos de Programación en Python

## Funcionalidades

- Menú de inicio con opción para jugar o salir.
- Selección de número de preguntas por nivel (1, 2 o 3).
- Niveles de dificultad: **Básico**, **Intermedio** y **Avanzado**.
- Preguntas seleccionadas de forma aleatoria y sin repetición.
- Mezcla aleatoria de alternativas en cada ejecución.
- Validación de todas las entradas del usuario.
- Retroalimentación inmediata sobre respuestas correctas o incorrectas.
- Estimulación del aprendizaje con estructura modular.

## Estructura del Proyecto

- `main.py`: controlador principal del juego.
- `validador.py`: validación de entradas del usuario.
- `level.py`: lógica de asignación de nivel según la pregunta.
- `shuffle.py`: mezcla aleatoria de alternativas.
- `question.py`: selección de preguntas no repetidas por nivel.
- `print_preguntas.py`: formateo e impresión de preguntas y alternativas.
- `verify.py`: verificación de respuestas correctas.
- `preguntas.py`: base de datos con preguntas y alternativas.

## Instrucciones de uso

1. Ejecutar el archivo `main.py`.
2. Seleccionar “1” para comenzar el juego.
3. Ingresar cuántas preguntas por nivel se desea responder (máx. 3).
4. Responder cada pregunta seleccionando la alternativa correcta (`a`, `b`, `c`, `d`).
5. Elegir si se desea continuar o salir tras cada pregunta.