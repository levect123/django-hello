# django-hello

descargar codigo py desde la siguiente direccion.
https://bootstrap.pypa.io/get-pip.py
	.guardar el codigo en un .py y ejecutarlo con el sigueinte comando:

	.python  (nombre del py)

una vez ejecutado  el archivo .py,  se debera ir al directorio donde se instalo PIP, ene ste caso es :
:\Python\Scripts

instalacion de virtualenv:
-pip install virtualenv
actualizar librerias:
-python -m pip install -U pip
ejecutar virtualenv:
-virtualenv .
-activate (ejecutar .bat de virtualenv)
-deactivate (desactivar .bat de virtualenv)

correr servidor 
dentro de la carpeta donde este el archivo manage.py executar:
python manage.py runserver


nuevo projecto
situarse en pip
-pip install virtualenvwrapper-win
*agregar a  variable de entorno a virtualenvwrapper
-mkdirvirtualenv <nombre de la carpeta>
-lsvirtualenv <- para listar los proyectos
ver la ruta donde creo el proyecto, ir alli y ejecutar activate.bat
instalar django en la carpeta del projecto. despues ejecutar django-admin.py startproject <nombre del proyecto>
posteriormente  arancar el sitio

migrar el servicio
python manage.py migrate