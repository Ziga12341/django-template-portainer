# django-template-portainer
this repo has django project exposed through network inside DNS (portainer)


create virtual environment with conda:

conda create -n django-template
conda activate django-template

create requirements.txt file
install requirements:
pip install --upgrade pip
pip install -r requirements.txt

create django project:
django-admin startproject django_template

create django app:
cd django_template
python manage.py startapp my_app

create .env file:
.env is in .gitignore file you need to create your own file

change settings.py file:
add dockerfile to project

need to add 'django-template.dev.razum.si' to ALLOWED_HOSTS.

page is available on:
https://django-template.dev.razum.si/

key:
SECRET_KEY='django-insecure-u7%38yg*%58alio35tw@+%_x=n*z_g(#4ij8@*f28r_bo4*=^6'