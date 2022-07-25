Pequeña aplicación hecha con una API (Quizzler) y una interfaz realizada en Tkinter.

La aplicación tiene por defecto 10 preguntas (que se le piden a la api) pero se puede ampliar.

Tiene varios archivos, los cuales se dividen en:

data.py: Hace una request a la api de quizzle con el número de preguntas, el tipo de preguntas (en este caso Boolean)
y la categoría

question_model.py: Clase donde se definen las preguntas, el avanzar y acertar.

quiz_brain.py: Es el cerebro del proyecto, es una clase donde define lo básico del programa (las preguntas que faltan,
comprobar las respuestas y avanzar las respuestas)

ui.py: Define la interfaz gráfica de la aplicación, está hecha en Tkinter.

main.py: Es la aplicación principal

NOTA: El proyecto se ha realizado en inglés por comodidad a la hora de escribir (ver tutoriales, la sintaxis del lenguaje...)

