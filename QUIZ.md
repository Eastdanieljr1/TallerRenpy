# QUIZ

```python

label QuizStart:
    $ QuizScore = 0
    $ Questions = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]  # Lista con los números de las preguntas
    $ renpy.random.shuffle(Questions)
    $ punto = 0

label Quiz:

    # Verifica si hay más preguntas por hacer
    
    if Questions:
        $ Question = Questions.pop()
    
        # Resto del código para cada pregunta...
        if Question == 1:
            menu:
                "Puedes tenerme, pero no puedo tocarte. Puedo estar en cualquier forma, aún así, nadie puede poseerme. ¿Quién soy?"
                "a) Tu palabra":
                    $ respuesta_pregunta_1 = "a"
                "b) Tu sombra":
                    $ respuesta_pregunta_1 = "b"
                "c) Un objeto invisible":
                    $ respuesta_pregunta_1 = "c"

            # Calcula los puntos para la pregunta 1...
            if respuesta_pregunta_1 == "a":
                $ punto += 1

        # Repite el patrón para las preguntas 2, 3, 4 y 5...
        elif Question == 2:
            menu:
                "Soy un número, si me añades a cualquier otro número, el resultado no cambia."
                "a) 10":
                    $ respuesta_pregunta_2 = "a"
                "b) 0":
                    $ respuesta_pregunta_2 = "b"
                "c) 15":
                    $ respuesta_pregunta_2 = "c"

            # Calcula los puntos para la pregunta 2...
            if respuesta_pregunta_2 == "b":
                $ punto += 1

        elif Question == 3:
            menu:
                "Tengo llaves pero no puedo abrir cerraduras. Tengo espacio pero no tengo habitación. ¿Qué soy?"
                "a) Un coche":
                    $ respuesta_pregunta_3 = "a"
                "b) Un llavero":
                    $ respuesta_pregunta_3 = "b"
                "c) Una caja fuerte":
                    $ respuesta_pregunta_3 = "c"

            # Calcula los puntos para la pregunta 3...
            if respuesta_pregunta_3 == "b":
                $ punto += 1

        elif Question == 4:
            menu:
                "Tengo llaves pero no puedo abrir cerraduras. Tengo espacio pero no tengo habitación. ¿Qué soy?"
                "a) Un coche":
                    $ respuesta_pregunta_3 = "a"
                "b) Un llavero":
                    $ respuesta_pregunta_3 = "b"
                "c) Una caja fuerte":
                    $ respuesta_pregunta_3 = "c"

            # Calcula los puntos para la pregunta 3...
            if respuesta_pregunta_3 == "b":
                $ punto += 1
        # Repite el patrón para las preguntas 4 y 5...
        
        elif Question == 5:
            menu:
                "Tengo llaves pero no puedo abrir cerraduras. Tengo espacio pero no tengo habitación. ¿Qué soy?"
                "a) Un coche":
                    $ respuesta_pregunta_3 = "a"
                "b) Un llavero":
                    $ respuesta_pregunta_3 = "b"
                "c) Una caja fuerte":
                    $ respuesta_pregunta_3 = "c"

            # Calcula los puntos para la pregunta 3...
            if respuesta_pregunta_3 == "b":
                $ punto += 1

        elif Question == 6:
            menu:
                "Puedo viajar por el mundo mientras permanezco en un rincón. ¿Qué soy?"
                "a) Un sello":
                    $respuesta_pregunta_6 = "a"
                "b) Una carta":
                    $respuesta_pregunta_6 = "b"
                "c) Una maleta":
                    $respuesta_pregunta_6 = "c"

            # Calcula los puntos para la pregunta 6...
            if respuesta_pregunta_6 == "a":
                $punto += 1

        elif Question == 7:
            menu:
                "Tengo llaves pero no puedo abrir ninguna cerradura. ¿Qué soy?"
                "a) Una guitarra":
                    $respuesta_pregunta_7 = "a"
                "b) Un piano":
                    $respuesta_pregunta_7 = "b"
                "c) Un acordeón":
                    $respuesta_pregunta_7 = "c"

            # Calcula los puntos para la pregunta 7...
            if respuesta_pregunta_7 == "b":
                $punto += 1

        elif Question == 8:
            menu:
                "Soy más poderoso que los dioses, más malvado que el diablo, los ricos lo necesitan, los pobres lo tienen, y si lo comes, morirás. ¿Qué soy?"
                "a) Nada":
                    $respuesta_pregunta_8 = "a"
                "b) El tiempo":
                    $respuesta_pregunta_8 = "b"
                "c) La vida":
                    $respuesta_pregunta_8 = "c"

            # Calcula los puntos para la pregunta 8...
            if respuesta_pregunta_8 == "b":
                $punto += 1

        elif Question == 9:
            menu:
                "Puedo ser largo o corto, pero nunca alto. ¿Qué soy?"
                "a) Un camino":
                    $respuesta_pregunta_9 = "a"
                "b) Un río":
                    $respuesta_pregunta_9 = "b"
                "c) Un discurso":
                    $respuesta_pregunta_9 = "c"

            # Calcula los puntos para la pregunta 9...
            if respuesta_pregunta_9 == "c":
                $punto += 1

        elif Question == 10:
            menu:
                "Si lo nombras, rompes. ¿Qué es?"
                "a) Un huevo":
                    $respuesta_pregunta_10 = "a"
                "b) Un silencio":
                    $respuesta_pregunta_10 = "b"
                "c) Un cristal":
                    $respuesta_pregunta_10 = "c"

            # Calcula los puntos para la pregunta 10...
            if respuesta_pregunta_10 == "b":
                $punto += 1
        jump Quiz
    else:
        jump ShowQuizResults  # Todas las preguntas han sido respondidas, muestra los resultados

label ShowQuizResults:


# Resto del código...

```
