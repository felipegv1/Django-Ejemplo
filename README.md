# Django-Ejemplo

Ejemplo Basico Django

## Pasos

pip install django

Luego de haber descargado el proyecto:
En la carpeta del proyecto
python manage.py runserver

## Ir a la url

Antes de ir a la url ejecutar:
python manage.py makemigrations
python manage.py migrate

url:
http://127.0.0.1:8000/usuarios/

## Agregar usuario

Para ver algun dato en la url primero agregar un usuario:

Desde la consola:
python manage.py shell

from app.models import Usuario
nuevo_usuario = Usuario(nombre='Nombre del Usuario', correo='correo@ejemplo.com')
nuevo_usuario.save()
exit()
