# README

Este es un proyecto simple de encuestas en Django siguiendo el tutorial de la documentación: https://docs.djangoproject.com/en/5.1/intro/tutorial01/.
Tiene además lógica de autenticación y requiere estar logueado para acceder a todas las vistas.

### Pasos para levantar el projecto

#### Correr las migraciones

```bash
python manage.py migrate
```

#### Crear un usuario inicial (superusuario)

```bash
python manage.py createsuperuser
```

#### Levantar el proyecto

```
python manage.py runserver
```
