# Projecto-blog-1
Este es un proyecto de blog funcional desarrollado en Django. Permite listar publicaciones, ver los detalles de cada una y agregar nuevas publicaciones desde la web.
- Página de inicio: Lista todas las publicaciones con título, extracto del contenido y fecha.
- Vista detallada: Muestra el contenido completo de cada publicación al hacer clic en su título.
-Panel de administración: Permite agregar y administrar posts desde el panel de administración de Django.

Instalación 
Accede al directorio del proyecto: cd tu-repositorio
Crea un entorno virtual e instálalo:python -m venv env
env\Scripts\activate
pip install -r requirements.txt
Realiza las migraciones: python manage.py migrate
Ejecuta el servidor local:python manage.py runserver
ccede al blog en: http://localhost:8000

¿Cómo usar?
En la página de inicio, podrás ver todos los posts existentes.
Haz clic en un título para ver los detalles completos del post.
Para agregar nuevos posts, accede al panel de administración de Django en http://localhost:8000/admin y usa el formulario de "Posts".
