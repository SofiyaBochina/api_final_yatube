# Yatube API
Учебный проект "API сервиса Yatube".

## Как запустить проект

В командной строке клонируйте проект и перейдите в него:
```
git clone https://github.com/SofiyaBochina/api_final_yatube
```
```
cd api_final_yatube
```
Создайте и активируйте виртуальное окружение:
```
python -m venv venv
```
```
source venv/Scripts/activate
```
Установите зависимости:
```
pip install -r requirements.txt
```
Перейдите в папку yatube_api:
```
cd yatube_api
```
Создайте и выполните миграции:
```
python manage.py makemigrations
```
```
python manage.py migrate
```
Запустите проект:
```
python manage.py runserver
```
## Документация API Yatube
После запуска проекта вам будет доступна документация проекта по адресу http://127.0.0.1:8000/redoc/, где описано, как работает проект, и представлены примеры доступных запросов.
