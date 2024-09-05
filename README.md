# Проект Kittygram

[![Main Kittygram workflow](https://github.com/Kirill374mansurov/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/Kirill374mansurov/kittygram_final/actions/workflows/main.yml)

## Описание

**Kittygram** - это проект, в котором пользователи в общее обозрение выкладывают своих котов и их достижения.

## Технологии

![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

## Авторы

### [Кирилл Мансуров](https://github.com/Kirill374mansurov)</br>  

## Функциональность

- Можно добавлять фотографию котов.
- Выбирать цвет из присутствующих.
- Брать доступные достижения или добавлять свои.

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
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
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
cd backend
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py makemigrations
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
