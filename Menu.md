# TallerRenpy

⚠️Importante

Primero vamos a ver el menu del escritorio

Si quieres un menu asi, deberas hacer las siguientes modificaciones en tu codigo

![imagen](https://github.com/user-attachments/assets/be219166-f8f6-4388-9d5a-c08b7e76fd6e)

Paso 1:
Deberas presionar las teclas shift+i para poder abrir el menu de informacion del sistema.

![imagen](https://github.com/user-attachments/assets/c738f5fa-6183-4acd-8b01-bedeff003657)

Una vez en el menu dirigete a ubicar la seccion que indica Screen main menu(Specificamente la parte de Vbox).
  
  Una vez visualizado en la seccion derecha indicara la linea de codigo donde se encuentra en el script.
    
  Debemos clickearlo para poder ir al codigo.(Nota: mayormente se encuentra en el script de Screen y en la linea de codigo 290)

(Lo que debemos modificar esta en la Linea de Codigo 293)
![imagen](https://github.com/user-attachments/assets/a4f12f12-e220-4e81-9ada-46f7a6e3768a)

Borraremos las lineas 293 y 294 
![imagen](https://github.com/user-attachments/assets/a88ef203-22f8-41f6-97f8-ed2eb9c56dbc)

Posteriormente escribiremos las siguientes lineas de codigo:
```python
        if main_menu:
            xalign 0.5
            yalign 0.7
        else:
            xoffset 60
        yalign 0.5
```
![imagen](https://github.com/user-attachments/assets/4f4e303f-3dcb-4c21-af88-d1a6d90ff311)

Advertencia asegurese que este igual a la imagen o tendra problemas de indentacion.




