# recipe-app-api
# Lista comandi utili

# Linting con Flake8
docker-compose run --rm app sh -c "flake8"

# Crea un progetto Django 
docker-compose run --rm app sh -c "django-admin startproject app ."

# Setup test con Django
docker-compose run --rm app sh -c "python manage.py test"
