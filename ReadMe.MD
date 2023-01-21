''' To install Virtual env'''
python3 -m venv myenv

'''Activate env''''
source myenv/bin/activate

'''create django project'''
django-admin startproject backend

''' create a django app '''
python manage.py startapp base