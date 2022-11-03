### Описание проекта:

Проект «API для Yatube» позволяет пользователям подписываться на авторов постов и комментировать понравившиеся записи.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/ifyoumasha/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
или
python -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
или
python manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
или
python manage.py runserver
```

Документация и примеры запросов доступны по адресу:

```
http://127.0.0.1:8000/redoc/
```
