(base) PS D:\DESARROLLO\DJANGO\Django-Holamundo_PumaBryan>

#Crear un etorno
conda create --name entorno_holamundo01 python = 3.10

#Activar entorno
$ conda activate entorno_holamundo01

#Desactivar entorno
$ conda deactivate

#Instalar Django
pip install Django==3.*

#Guardar un texto con todos los paquetes y versiones
pip freeze > requirements.txt

#Instalar todos los paquetes y versiones desde el listado
pip install -r .\requirements.txt
