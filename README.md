# Онлайн-магазин OnlineShop
***
1. Клонировать проект
```
Git clone https://github.com/Glory665/OnlineShop
```
2. Создать виртуальное окружение
```
python -m venv venv
source venv/bin/activate
```
3. Установить зависимости
```
pip install -r requirements.txt
Создать .env где вписать данные от телеграм
```
4. Запустить миграции, установить данные БД
```
python manage.py migrate
python manage.py loaddata data.json
```
5. Запустить сервер
```
python manage.py runserver
```
6. Радоваться
