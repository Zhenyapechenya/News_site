## Задача

Реализовать небольшой новостной сайт. Добавить к статьям  тематические разделы, к которым они относятся, и отображать их у каждой новости в виде списка тегов.

У каждой статьи может быть несколько разделов, но всегда один из них должен быть основным.
В списке тегов он должен идти первым, потом все остальные в алфавитном порядке.

В админке реализовать создание разделов и для страницы _Редактирование статьи_ добавить возможность указывать разделы.
Необходимо также реализовать проверку на наличие одного и только одного основного раздела.

**Примечание**: страницы для новостных статей в рамках задания не предусмотрены. 


## Результат
![Вывод тегов разделов](./res/with_tags.png)

## Документация по проекту

Для запуска проекта необходимо

Установить зависимости:

```bash
pip install -r requirements.txt
```

Провести миграцию:

```bash
python manage.py migrate
```

Загрузить тестовые данные:

```bash
python manage.py loaddata articles.json
```

Запустить отладочный веб-сервер проекта:

```bash
python manage.py runserver
```

Данные для входа в админку:
```bash
Логин: admin
Пароль: admin
```


## Задачу выполнила
Евгения Псарева `epsareva77@gmail.com`
