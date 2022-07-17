# Проект API YATUBE

### Описание
REST API для социальной сети YATUBE. Создан во время учебного курса Яндекс практикума.
Поддерживает методы GET, POST, PUT, PATCH, DELETE.
Аутентификация по токену.

### Технологии
- Django Rest Framework
- Язык Python 3.7


### Как запустить проект:


Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

Автор Хижняк Владислав
