### [Демонстрация проекта "Доска объявлений"](#1)
### [Описание проекта](#2)
### [Инструкция по запуску проекта](#3)

### <a name="1">Демонстрация проекта "Доска объявлений"</a>

Вход в проект

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/63869857/202278696-8e35f0ae-db8e-41b1-bd5d-e070429a3378.png">

Интерфейс проекта "Доска объявлений"

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/63869857/202280075-b54a11ba-c450-40fa-a561-e6905b370f59.png">

### <a name="2">Описание проекта</a>

Данный проект представляет собой доску объявлений. Каждый пользователь может просмотреть все объявления и добавить/изменить свое.

В данном проекте реализовано:

- функционал аутентификации Laravel, включая вход в систему, регистрацию (библиотека laravel/ui);
- создание объявления;
- редактирование и удаление объявления авторам данного объявления.

### <a name="3">Инструкция по запуску проекта</a> 

Скачать с GitHub:

    git clone https://github.com/al-zv/bboard.git
    
Настроить подключение к базе данных (настройки подключения к базе данных находятся в файле .env).    
    
Запустить проект (php должен быть установлен):

    php artisan serve

Выполнить миграции:

    php artisan migrate

Перейти на страницу путь к которой будет отображен после команды:

    php artisan serve
