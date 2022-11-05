# celery_test
Celery Test (celery + redis + django checklist)

Source: https://gist.github.com/bennett39/01be4802c42c3ef446b78388d1ba8d2d

pip install django
pip install celery
pip install redis

django-admin startproject config . //Start project

python manage.py runserver

python manage.py startapp cly //app

python manage.py migrate

![image](https://user-images.githubusercontent.com/91982815/200135847-97d1b45a-0dce-456d-b8c3-2e36ef551493.png)


celery -A config.celery worker --loglevel=info

