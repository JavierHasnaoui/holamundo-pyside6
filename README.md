# holamundo-pyside6
Hola Mundo con PySide6.      
  
Para ejecutar el _hola mundo_,necesitamos instalar antes Python3 y sus dependencias.

## Clonamos el proyecto en local y entramos en la carpeta del proyecto

```bash
git clone https://github.com/tuusuario/holamundo-pyside6.git
cd holamundo-pyside6
```
## Instalación de Python3
![2181](https://github.com/user-attachments/assets/8e55f5e3-0544-4301-83a1-73b039a99626)  
### Linux
Python viene preinstalado en la mayoria de distribuciones Linux, se puede comprobar si es está instalado ejecutando la siguiente orden en una terminal:
```bash
$python 3 --version
```
De no estar instalada , se puede descargar desde [aqui](https://www.python.org)  
Para más informacion de como instalar, consultar la [documentación.](https://pyspanishdoc.sourceforge.net/)
### Windows 
Descargar el instalador haciendo clic [aqui](https://www.microsoft.com/es-es/software-download/windows11) y seguir las instrucciones en pantalla.  
Se dispone de más informacion sobre su instalación en el siguiente [enlace](https://support.microsoft.com/es-es/windows/crear-medios-de-instalaci%C3%B3n-para-windows-99a58364-8c02-206f-aa6f-40c3b507420d).
### macOS
Se dispone del binario ejecutable en el siguiente [enlace.](https://support.apple.com/es-es/guide/terminal/apdd100908f-06b3-4e63-8a87-32e71241bab4/mac)  
Se dispone de más información sobre un instalación en el siguiente [enlace.](https://support.apple.com/es-es/102662)
## Creación de un entorno virtual(venv)
Para crear un entorno virtual y poder aislar la ejecución del resto del sistema(snadbox), ejecutamos la siguiente instrucción en una terminal.
```bash
$ python3 -m venv venv
```
## Activación del entorno virtual
### Linux y macOS
```bash
$ source ven/bin/activate
```
### Windows
```bash
$ venv\Scripts\activate.bat
```
### Instalación de dependencias
```bash
$ pip install -r requirements.txt
```
### Ejecución
```bash
python3 src/holamundo_pyside6/holamundo.py
```
Nos mostrará la aplicación _holamundo_pyside6_ en ejecución.  

![ejecutable](https://github.com/user-attachments/assets/2a4adb26-a143-418e-9ada-80056cb64d2e)
