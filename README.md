# Инструкция по запуску локального сайта

1. Клонируем проект
```git clone https://github.com/ilya-kan07/Django.git```
2. Создаем виртуальное окружение
```python -m venv venv ```
3. Активируем виртуальное окружение
```venv/scripts/activate```
4. Устанавливаем зависимости из файла **requirements.txt**
```pip install -r requirements.txt```
5. Применяем миграции к базе данных
```python manage.py migrate```
6. Создаем суперпользователя для дальнейшего создания и изменения постов на сайте
```python manage.py createsuperuser```
7. Запускаем сервер
```python manage.py runserver```
