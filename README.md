# holamundo-pyside6
Documentacion en Markdaown
# holamundo-pyside6

Hola mundo con PySide6.

Para ejecutar el Hola mundo, necesitamos instalar antes Python3 y sus dependencias.

## Clonamos el proyecto en local y entramos en la carpeta del proyecto

```sh
git clone https://github.com/tu-usuario/holamundo-pyside6.git
cd holamundo-pyside6
```

## Instalación de Python3

![Python](https://www.python.org/static/community_logos/python-logo.png)

### Linux
Python3 viene preinstalado en la mayoría de distribuciones Linux, pero puede comprobar si está instalado ejecutando la siguiente orden en una terminal:

```sh
python3 --version
```

De no estar instalado, se puede descargar desde [aquí](https://www.python.org/downloads/).

### Windows
Descargar el instalador haciendo clic [aquí](https://www.python.org/downloads/windows/) y seguir las instrucciones en pantalla.

Para más información sobre su instalación, consulte la [documentación](https://docs.python.org/3/using/windows.html).

### macOS
Se dispone del binario ejecutable en el siguiente [enlace](https://www.python.org/downloads/macos/).

## Creación de un entorno virtual (venv)

Para crear un entorno virtual y poder aislar la ejecución del resto del sistema (sandbox), ejecutamos la siguiente instrucción en una terminal:

```sh
python3 -m venv venv
```

## Activación del entorno virtual

### Linux y macOS

```sh
source venv/bin/activate
```

### Windows

```sh
venv\Scripts\activate.bat
```

## Instalación de dependencias

```sh
pip install -r requirements.txt
```

## Ejecución

```sh
python3 src/holamundo_pyside6/holamundo.py
```

Nos mostrará la aplicación `holamundo_pyside6` en ejecución.

![PySide6 Hola Mundo](https://via.placeholder.com/150?text=Hola+Mundo%21)


