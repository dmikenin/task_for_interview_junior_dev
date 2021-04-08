# Task for interview junior developer

For junior developers, which i interview in company, i give test task for check skills and detect problems.

- [english version](#english)
- [russian version](#russian)

<br>

### <a name="english"></a> Enaglish version
Test Assignment: You need to develop a REST API on Django(Python). DATABASE: PostgreSQL

Application description: Blog. The REST will have to display articles. Articles can be created and edited in the admin panel. Each article can have a set of tags. User must be logged in with email and password.

What needs to be done:

0. Create a project, think up a database schema and implement it (need to use Foreign Key, M2M as appropriate). Do at least 2 migrations
1. Make registration/authorization through REST API, with JWT.
2. Make endpoint of 1 post, only for authorized user
3. Make endpoint for display all posts, only for authorized user
4. Ability to sort all posts from old to new and vice versa. By default output "newest"
5. POST request to create an message to administration
6. Admin. On the page with all the articles, should work: sorting by date, search, displayed fields (article title, published (yes / no), date created). All this using the built-in features of Django
7. Admin pages. Make an admin page for all models.
8. Admin page. On the edit page of an article there should be an add tag admin page. Use the built-in features of Django
9. Admin. Only superuser can authorize in admin, other users can't.
10. Make a swagger for all endpoints.

Hard task: in order for a user to be able to authorize with an email and password, you need to override the basic User model.

<br>

### <a name="russian"></a> Russian version
Тестовое задание: Нужно разработать REST API на Django(Python). БД: PostgreSQL

Описание приложения: Блог. REST должен будет выводить статьи. В админке статьи создавать и редактировать. У каждой статьи может быть набор тегов. Пользователь должен авторизоватьсся при помощи email и пароля.

Что нужно сделать:

0. Создать проект, придумать схему БД и реализовать ее (нужно использовать Foreign Key, M2M по ситуации). Сделать как минимум 2 миграции
1. Сделать регистрацию/авторизацию через REST API, с JWT.
2. Сделать вывод 1 поста только для авторизованного пользователя
3. Сделать вывод всех постов только для авторизованного пользователя
4. Возможность сортировки всех постов от старых к новым и наоборот. По умолчанию выводить "по-свежести"
5. POST запрос для создания обращения к администрации
6. Админка. На странице со всеми статьями, должны работать: сортировка по дате, поиск, выводиться поля(название статьи, опубликован(да/нет), дата создания). Все это с использованием встроенных возможностей Джанго
7. Админка. Сделать админ страницы для всех моделей.
8. Админка. На странице редактирования 1 статьи должна быть еще встроена админ страница добавления тегов. Использовать встроенные возможности Джанго
9. Админка. В админке может авторизоваться только суперюзер, другие пользователи не могут.
10. Оформить сваггер для всех ручек

Задание со звездочкой: для того, чтобы пользователь мог авторизоваться с помощью email и пароля, нужно переопределить базовую модель User.
