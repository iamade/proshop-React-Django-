''' To install Virtual env'''
python3 -m venv myenv



'''Activate env''''
source myenv/bin/activate

''' To iNstall Django '''
pip3 install django

'''create django project'''
django-admin startproject backend

''' create a django app '''
python manage.py startapp base

'''install restframework '''
pip3 install djangorestframework

'''django migrations'''
python manage.py migrate

'''create superuser '''
python manage.py createsuperuser

kaskatgtwo

''' After creating a model run '''
python manage.py makemigrations 
python manage.py migrate

'''image processing library'''
pip install pillow


'''redux installation'''
npm install redux react-redux redux-thunk redux-devtools-extension