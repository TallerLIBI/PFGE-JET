### PARA VISUALIZAR UNA IMAGEN EN PYTHON

Antes de instalar alguna libreria que me permitiera procesar imagenes, lo que hice fue ejecutar un comando que me permitiera instalar las librerias que requiero para Python.

Debido a lo anterior, instale **pip** (permite instalar paquetes o modulos para Python)

###Para linux: 
NOTA:debo hacerlo desde la consola , no desde Python!!!!!

```
$ sudo apt-get install python-pip
```
______________________________________________________________________________________

### Para el caso de Windows:
NOTA:No lo he comprobado!!!

1. Ir a la siguiente dirección: https://bootstrap.pypa.io/get-pip.py 
2. Guardar el archivo (get-pip.py)
3. Abrir la **consola de Windows (CDM)**
4. Posicionarse en el directorio donde guardamos el archivo que descargamos (get-pip.py)
5. Ejecutar : **$ python get-pip.py**

__________________________________________________________________________________________



Una vez que instalé **pip** ... desde la consola (sin estar en Python) instalé la librería **PIL** , porque me va a permitir procesar imágenes.

- Para instalar la librería ejecuté el siguientes comando 

```
 $ sudo apt-get install python-imaging
```

NOTA: No funcionó!!!

Sin embargo, encontré que también se pueden instalar las librerías PIL (pillow) desde **pip**, con cualquiera de los siguientes comandos

```
$ pip install pillow
$ apt-get install python-pillow
```

Entonces ejecute:

```
$ sudo apt-get install python-pillow

```
Agregué **sudo**, porque estoy utilizando linux





