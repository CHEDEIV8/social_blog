# Проект: **social_blog**
---

### Стек:

Python 3.7 , Django, SQLite 3, Pillow, Unittes

---

### Описание: 
**social_blog** - это социальная сеть с авторизацией, персональными лентами, комментариями. Так-же позволяет делится тем, что вам нравится и подписываться на тех авторов которые предоставляют интересный контент



###  В проекте реализованы следующие функции:

**Авторизованному** пользователю доступно:
- Добавление/удаление постов авторизованными пользователями
- Редактирование постов только его автором
- Возможность авторизованным пользователям оставлять комментарии к постам
- Подписка/отписка на понравившихся авторов
- Создание отдельной ленты с постами авторов, на которых подписан пользователь
- Создание отдельной ленты постов по группам(тематикам)

**Неавторизованному** пользователю доступно только чтение.

Так же в проекте подключены:
- Пагинация
- Кеширование
- Авторизация пользователя
- Возможна смена пароля через почту

Дополнительно:
- Покрытие тестами

---
## Запуск проекта в dev-режиме

\- Клонировать репозиторий
```
git@github.com:CHEDEIV8/social_blog.git
```
\- Перейти в папку с проектом
\- Установить виртуальное окружение для проекта;
```
python -m venv venv
```
\- Активировать виртуальное окружение для проекта:
Для OS Lunix и MacOS
```
source venv/bin/activate
```
Для OS Windows
```
source venv/Scripts/activate
```

\- Установить зависимости:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
\- Выполнить миграции на уровне проекта:
```
cd social_blog
python3 manage.py makemigrations
python3 manage.py migrate
Запустить проект локально:
python3 manage.py runserver
```
### Aдрес запущенного проекта
http://127.0.0.1:8000

\- Зарегистирировать суперпользователя Django:
```
python3 manage.py createsuperuser
```
### Адрес панели администратора
http://127.0.0.1:8000/admin

---
Автор проекта: **Денис Чередниченко**
