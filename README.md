### Kittygram
Kittygram — это инновационная социальная сеть, созданная специально для любителей животных. В Kittygram пользователи могут делиться фотографиями своих любимых питомцев, обмениваться впечатлениями и находить единомышленников по всему миру.
Kittygram — идеальное место для тех, кто хочет делиться радостью общения с питомцами и находить новых друзей среди любителей животных.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/p1mcky/kittygram_fn.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

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

### Технологии
- Python
- Django
- Django Rest Framework
- Gunicorn
- Nginx
- Docker
- PostgreSQL

### Автор
Супонин Кирилл