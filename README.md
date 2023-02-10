# DJANGO PORTAFOLIO

## Descripción
Portafolio para ver y agregar proyectos.

## Setup

Crear un entorno virtual y lo activamos:

```sh
python virtualenv venv
# windows
source venv/Scripts/activate
```

Luego instalar las librerias:

```sh
pip install -r requirements.txt
```

Luego ejecutamos las migraciones para crear la base de datos de nuesta aplicacion, todo dentro de nuestro entorno virtual
```sh

python manage.py makemigrations
python manage.py migrate

```

Una vez concluido, procedemos a iniciar la app

```sh
python manage.py runserver
```