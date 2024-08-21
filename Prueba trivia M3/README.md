# Prueba - Fundamentos de programación en Python
##### Prueba - Fundamentos de programación en Python correspondiente al bootcamp fullstack python.

Este repositorio contiene el archivos para ejecutar "main.py" y otros archivos anexos a este:

* **main.py:** Archivo principal que ejecuta la trivia.
* **preguntas.py:** Contiene los diccionarios con las preguntas y alternativas.
* **validador.py:** Contiene la función para validar las opciones ingresadas por el usuario.
* **level.py:** Contiene la función para elegir el nivel de dificultad de la pregunta.
* **shuffle.py:** Contiene la función para mezclar las alternativas de una pregunta.
* **question.py:** Contiene la función para elegir una pregunta al azar y sus alternativas.
* **print_preguntas.py:** Contiene la función para imprimir una pregunta y sus alternativas formateadas.
* **verify.py:** Contiene la función para verificar si la respuesta del usuario es correcta.

## Requisitos para ejecutar
* Sistema operativo Windows, MacOS o Linux
* Python 3.12 o superior
* tener todos los archivos en una misma carpeta

## Programa

### main.py

Este programa cumple la funcion de ser una trivia interactiva donde el mismo jugador define el número de preguntas a responder correspondientes a cada nivel de dificultad, y gana al responder todas las preguntas correctamente.seleccionados

#### Ejecución
* Ejecutar por terminal main.py, el cual comenzara la trivia, preguntará si desea jugar 
* luego preguntara la cantidad de preguntas por nivel de dificultad con las que desea jugar
* comienzan las preguntas, donde el jugador debe responder con a,b,c o d, segun crea que es la respuesta correcta

#### Ejemplo:

sh

python main.py

Respuesta esperada:

Bienvenido a la Trivia        
Ingrese una opción para Jugar!
        1. Jugar
        0. Salir

    > 1
¿Cuántas preguntas por nivel? (Máximo 3):
    > 2

Pregunta 1:
¿Cuál es el océano más grande del mundo?
A. Indico
B. Atlantico
C. Pacifico
D. Artico
Escoja la alternativa correcta:

    >c

Muy bien, sigue así!
¿Desea continuar? [y/n]:

    >y

Pregunta 2:
¿Qué planeta es conocido como el "Planeta Rojo"?
A. Venus
B. Jupiter
C. Marte
D. Mercurio
Escoja la alternativa correcta:

    >d

Lo siento, conseguiste 1 respuestas correctas,
 ¡Sigue participando!


## Autor

Grupo 1 bootcamp full stack python G20