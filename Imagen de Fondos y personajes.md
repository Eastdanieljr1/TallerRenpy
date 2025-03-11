# Fondos

Primero debes obtener los fondos necesarios para tu proyecto,si no los tienes puedes obtenerlos de la pagina itch.io

https://itch.io/game-assets/genre-visual-novel/tag-backgrounds

![imagen](https://github.com/user-attachments/assets/a9b5b54a-fa7d-4ebd-a052-7ea1f4340b38)

Una vez ahi, deberas escoger tus fondos(Solo asegurate de las especificaciones del autor.)

![imagen](https://github.com/user-attachments/assets/7644f2e2-65ab-4835-8580-f8ae6f9a03ab)

clickea  en Descargar

![imagen](https://github.com/user-attachments/assets/11e78946-a073-498a-afcb-63f75a0baf15)

y aseguarate de darle click a donde dice "No, gracias enviame a los links"

![imagen](https://github.com/user-attachments/assets/37d73313-6d01-4f44-9b2e-c02f9e8862f2)

Una vez tengas descargados tus Fondos Procederas a hacer lo mismo con los personajes. en caso que tuviera fallas en este git dejare los archivos correspondientes.


# Creacion de atributos 

Primero debemos archivar nuestro fondos y personajes en la carpeta correspodiente del proyecto, para ello debemos irnos al menu de renpy.

Y donde indica abrir carpetas, debemos presionar/clickear donde dice images

![imagen](https://github.com/user-attachments/assets/e9aa7689-e811-402d-bf8b-34c9f3928ba2)

Una vez abierto debemos pegar los archivos(Asegurate de crear carpetas para los fondos y personajes.)


![imagen](https://github.com/user-attachments/assets/17c965ac-0c73-4f34-a503-c065da2a8b09)


Una vez hecho, ahora debemos crear sus atributos.

Para ello debemos de irnos a nuestro archivo Script.rpy(Si no sabes donde encontrarla,Ve al menu de renpy a un costado aparecera)

Una vez abierto debemos esctibir 

1.- Personajes.

python

#ESTE ES UN EJEMPLO
image define Nombre del atributo="Nombre del personaje o Fondo.formato de la imagen"

#Como debe quedar(Para un personaje)

image define leo serio = "side leo serio.png"

#EJEMPLO FONDOS

image Nombre del atributo = "nombre del fondo.formato de la imagen"

#Como debe quedar(Para un fondo)

#Nota los Fondos estan en images, Pero como se creo una Carpeta con el mismo nombre deberas indicarlo antes del nomnbre del fondo

image cuarto = "fondos/cuarto.png"



Una vez creado para poder utilazarlo deberas simplemente escribir

‵‵‵python
#para los personajes y fondos

#para mostrarlo

show leo serio

show cuarto

#para dejar de mostrarlo

hide leo serio

hide cuarto


‵‵‵

Y eso seria todo para los fondos. Hay mas cosas por ver pero el tiempo es limitado.




