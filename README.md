# Проект команды devsTeam.getName()

<div>

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![SkyPro](https://img.shields.io/badge/SkyPro-green?style=for-the-badge&logo=skypro&logoColor=white)
![JetBrains](https://img.shields.io/badge/IntelliJ%20IDEA-java-blue?style=for-the-badge&logo=jetbrains&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-green?style=for-the-badge&logo=spring&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-blue?style=for-the-badge&logo=docker&logoColor=white)
</div>
<li><a href="https://skyengpublic.notion.site/64113e0a2641475c9ad9bea93144afff">Техническое задание на проект</a></li>

## Разработчики команды: 
Евгения Ганич, Антон Февралев, Руслан Черемисин, Дмитрий Рубцов.

## Краткое описание (подробно в Wiki проекта):

Сайт для продажи или перепродажи товаров. Пользователи могут размещать объявления и оставлять комментарии к объявлениям друг друга.
Реализованы следующие функции:

- Авторизация и аутентификация пользователей
- Распределение ролей между пользователями: пользователь и администратор
- CRUD для объявлений на сайте
- CRUD для комментариев к объявлениям
- Администраторы могут удалять или редактировать все объявления и комментарии. Пользователи могут создавать, удалять или редактировать свои собственные
- Поиск объявлений по названию в шапке сайта
- Загрузка и отображение изображений объявлений и аватаров пользователей

___

## Технологии проекта
* Backend:
    - Java 11, Maven
    - Spring Boot, Spring Web, Spring Data, Spring JPA, Spring Security
    - Lombok
    - Stream API    
    - REST
    - GIT
* Datebase:
    - PostgreSQL
    - Liquibase
* Frontend:
    - Docker
    - Postman
---
## Запуск приложения
* Для запуска приложения Вам потребуется выполнить несколько шагов:
    - Клонирование проекта в среду разработки (**IntelliJ IDEA**);
    - В файле **application.properties** указать путь к Вашей базе данных;
    - Запустите **PostgreSQL** и получите доступ к БД;
    - Запустите **Docker**;
    - Запустите **Docker image**;
    - Запустите приложение (метод **main** в файле **HomeworkApplication.java**);

**После выполнения всех шагов веб-сайт будет доступен по адресу** http://localhost:3000
