# Creacion de personajes

Para poder usar un personajes primero debemos crearlo en script

Para ello primero debemos irnos a renpy y en la seccion editar archivo hacerle clic al archivo script.rpy

![imagen](https://github.com/user-attachments/assets/f842790c-b612-4986-a8ec-aad0f62ffe02)

Una vez abierto debemos crear los personajes.

para ellos escribiremos los siguiente.

```python

#character leo es el nombre que tendra nuestro atributo para poder llamarlo mas comodamente en las siguientes lineas de codigo

#Character especifica de que se trata en es este caso de un personajes

#"Leo" indica el nombre que aparecera en cuadro de dialogo

#image indica que en dado caso leo tenga una imagen predetermina la muestre(recomiendo no ponerla )

#color indica el colo que tendra el dialogo del personaje 

define character_leo = Character('Leo',image='i_leo',color="#93ff17")

```

Algo asi debe de quedar.

![imagen](https://github.com/user-attachments/assets/87da9f07-c6e1-4c24-a546-20b2a8656ad1)

# Convocar para que hable

Una vez que lo creamos ahora podemos hacer que diga un cuadro de dialogo, para ello debemos escribir lo siguiente.

```python
#como se mostro antes el atributo debe estar igual a como lo indicaste  define character_leo
# entre comilas va el cuadro de dialogo del personajes, ahi deberar escribir lo que quieras que diga el personajes
character_leo "¡Hola, Sofía! He oído hablar de tu destreza con los RompeCabezas. Tengo aquí un enigma que me ha estado desconcertando. ¿Te importaría echarle un vistazo?"

```

cuando ejecutes el juego el dialogo aparecera asi.(Nota no te preucupes si no aparece el personaje eso se vera mas adelante.)

![imagen](https://github.com/user-attachments/assets/88933ba5-7877-4a4a-8df3-7da4fbd0eac4)


