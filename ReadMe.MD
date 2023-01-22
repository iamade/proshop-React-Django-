''' To install Virtual env'''
python3 -m venv myenv

'''Activate env''''
source myenv/bin/activate

'''create django project'''
django-admin startproject backend

''' create a django app '''
python manage.py startapp base

'''django migrations'''
python manage.py migrate

'''create superuser '''
python manage.py createsuperuser

kaskatgtwo

''' After creating a model run '''
python manage.py makemigrations 
python manage.py migrate