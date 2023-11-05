
# Проект Kittygram, постите фото своих питомцев и пишите про их привички.

### Технологии
- Python
- Django
- SQLite
- NGINX
- Gunicorn


### Как запустить проект:

1. Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Fedor-new-Hope/infra_sprint1.git

cd infra_sprint1/
```

2. Cоздать и активировать виртуальное окружение:

```
python -m venv venv

source venv/scripts/activate
```

3. Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip

pip install -r requirements.txt
```

4. Выполнить миграции:

```
python manage.py migrate
```

5. Запустить проект:

```
python manage.py runserver 0:8080
```
  
**Проект будет доступен по адресу:**  
http://localhost:8080/