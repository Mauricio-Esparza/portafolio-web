### clase 11

```sh

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

'''sh 


pip es el sistema de gestión de paquetes. Es la herramienta que usamos para instalar, actualizar o desinstalar bibliotecas y módulos externos, como requests, numpy o flask.
Actualizamos pip por varias razones:
- Compatibilidad: Las versiones más recientes de Python o de ciertos paquetes pueden requerir una versión actualizada de pip.
- Seguridad: Las actualizaciones corrigen vulnerabilidades que podrían ser explotadas.
- Nuevas funciones: Cada versión nueva puede traer mejoras de rendimiento o nuevas capacidades.
- Corrección de errores: Se solucionan fallos que podrían afectar la instalación de paquetes.
