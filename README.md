# Шаблон Django-приложения

Шаблон подготовлен к деплою на Heroku: установлен whitenoise для обслуживания статики, веб-сервер gunicorn, описаны файлы runtime.txt и Procfile.

Версия Python, которая будет установлена на Heroku, описана в файле runtime.txt

Установлен pip-пакет djangorestframework (+djangorestframework-jwt).

### Запуск

```shell script
python -m venv env

# для Windows
source env/Scripts/activate

# для UNIX
source env/bin/activate

pip install -r requirements.txt

python manage.py runserver
```
