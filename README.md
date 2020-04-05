-- Iniciar aplicaciones nuevas
python manage.py startapp <Nombre app>

-- Crear modelos de tablas
Todo se hace en models.py
Luego hay que ejecutar python manage.py makemigrations <NOMBRE_APP>
Despues python manage.py migrate para aplicar esos cambios

-- Iniciar el portal
python manage.py runserver
El portal se publica en http://127.0.0.1:8000/

-- Cambios en la DB
Siempre que terminemos de hacer cambios que afecten a la DB, hay que aplicar el comando python manage.py makemigrations <Nombre de la app que tenga cambios>

-- Archivos
- settings.py 
Incluye las apps que vayamos creando dentro del proyecto. Esto se hace en INSTALLED_APPS. Tambien se incluyen las demas configuraciones como la DB, 
- models.py
Incluye los objetos de un aplicativo.