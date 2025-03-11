# 🎨 Taller Ren'Py

# ⚠️ Importante

Antes de comenzar, veremos cómo modificar el menú del escritorio en Ren'Py.

Si quieres un menú similar, sigue estos pasos para hacer las modificaciones necesarias en tu código.

![imagen](https://github.com/user-attachments/assets/be219166-f8f6-4388-9d5a-c08b7e76fd6e)

🖥️ Paso 1: Acceder al Menú de Información del Sistema

Presiona las teclas Shift + I para abrir el menú de información del sistema.

![imagen](https://github.com/user-attachments/assets/c738f5fa-6183-4acd-8b01-bedeff003657)

En el menú, ubica la sección que indica Screen main menu (específicamente en la parte de Vbox).



En la parte derecha se indicará la línea de código donde se encuentra este Screen en el script.

Haz clic en la línea de código para acceder al script. (Nota: Generalmente se encuentra en el script Screen en la línea de código 290.)

(Lo que debemos modificar esta en la Linea de Codigo 293)
![imagen](https://github.com/user-attachments/assets/a4f12f12-e220-4e81-9ada-46f7a6e3768a)

✏️ Paso 2: Modificar el Código

Ubica la línea 293 dentro del código.

Borra las líneas 293 y 294.
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

Asegúrate de que la indentación es correcta o podrías tener errores al ejecutar el proyecto.

✅ Con estos cambios, el menú de Ren'Py se verá modificado con la nueva alineación.

📌 Si tienes dudas, revisa que los cambios sean iguales a las imágenes o revisa la indentación del código. 🚀



