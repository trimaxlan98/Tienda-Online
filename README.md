# Tienda-Online
Proyecto de django base para una tienda online, no es un proyecto terminado solo sirve de plantilla para futuros proyectos

django-admin startproyect <Nombre proyecto>
  
python manage.py startapp <Nombre app>
  
python manage.py check <nombreApp>
python manage.py makemigrations
python manage.py sqlmigrate gestionPedidos <version>
python manage.py migrate
python manage.py shell
from gstionPedidos.models import Articulos
art=Articulos(nombre='mesa',seccion='decoracion',precio=90)
art.save()
art=Articulos.objects.get(id=1)
art.delete()
Lista=Articulos.objects.all()
Lista
Lista.query.__str__
