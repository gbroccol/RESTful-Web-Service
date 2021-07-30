# :pushpin: RESTful-Web-Service (2021)

<!-- ## Запуск:
1. http://127.0.0.1:8080/course -->

## :bulb: Технический стек:
- [x] Java
- [x] Spring Framework
- [x] Spring Boot
- [x] Spring Data
- [ ] Spring Security
- [x] 
- [ ] 
- [ ] **HTML, CSS, SCSS**
- [x] **Thymeleaf**
- [x] 
- [x] 
<!-- - [x] **MVC** - обработка HTTP запросов -->
- [x] **PostgreSQL**
- [x] **Spring Data JPA + Hibernate** - взаимодействие с БД
- [ ] **Spring security** - авторизация и аутентификация
- [ ] **minIO** для хранения файлов видео
- [ ] **clickhouse** (собирать и логировать статистику по движениям по сайту)

<!-- - [x] **Spring Core**
- [x] **Spring Boot** -->


##  :bulb: Цель
разработать образовательную платформу (как, например, Coursera, edX, Udacity, etc.)

## :bulb: Задачи:

### :small_red_triangle_down: Три группы пользователей с разными use-case'ами взаимодействия с платформой:

Возможности для взаимодействия с платформой расширяются от *ученика* к *администратору*, причем возможности каждой из групп включают в себя возможности предыдущей.

- [x] Ученики
- [ ] Преподаватели
- [ ] Администраторы

### :small_red_triangle_down: Глоссарий

**Курс** - это последовательность уроков 
- [x] Описание курса
- [x] Оглавление (список уроков)
- [ ] Вступительное видео
- [x] Добавить урок
- [x] Удалить урок
- [x] Изменить урок

**Упражнения**
- [ ] текст для прочтения / видео / тест
- [ ] Интерпретатор кода с проверкой решения задачи 

**Библиотека** — набор курсов ученика, которые он положил в закладки (студент не обязан проходить курс, находящийся в его библиотеке)
- [x] добавить курс в "Мои курсы"
- [x] удалить курс из вкладки "Мои курсы"

### :small_red_triangle_down: Ученик
- [ ] Регистрируется на платформе.
- [x] Может пользоваться поиском по курсам.
- [x] Добавляет курсы в свою библиотеку.
- [ ] Просматривает курс (описание, оглавление, вступительное видео).
- [ ] Статистика прохождения студентом его курсов из библиотеки.
- [ ] Отправляет сообщения преподавателю чтобы спросить что-то, etc.
- [ ] Получает сертификат о прохождении после завершения курса.

### :small_red_triangle_down: Преподаватель

- [ ] Регистрируется как ученик, по запросу верифицируется администратором как преподаватель.
- [ ] Редактирует курс — создает его, описывает его структуру (создает/удаляет/редактирует упражнения).
- [ ] Смотрит информацию (статистику) о прохождении курса: какие ученики прошли курс, на сколько они его прошли, как именно — то есть такая статистика должна собираться. Каждый преподаватель должен иметь доступ только к своим курсам
- [ ] Отправляет сообщения ученикам в качестве обратной связи.

### :small_red_triangle_down: Администратор

- [ ] Может удалять контент, выкладываемый преподователями и генерируемый учениками. (например, в случае нарушения правил платформы или законодательства страны).
- [ ] Может блокировать (и разблокировывать), удалять пользователей — как учеников, так и преподавателей (по тем же причинам).
- [ ] Подтверждает статус преподователей.


## :bulb: Useful links
1. Архитектура приложения
   * ["Чистая архитектура" Роберт Мартин](https://vk.com/doc44301783_469642449?hash=2e7f405cf8d7e96a43&dl=5af840b9982acd79a9)
   * ["Информационная архитектура"]()
   * ["Архитектура программного обеспечения на практике"](https://www.ozon.ru/context/detail/id/2456415/)
2. Spring Framework
   * [Spring Framework (Аннотации)](https://ru.wikibooks.org/wiki/Spring_Framework_Guide)
   * [Spring MVC — основные принципы](https://habr.com/ru/post/336816/)
   * [Что такое Spring Framework? От внедрения зависимостей до Web MVC](https://habr.com/ru/post/490586/)
   * [Dependency_injection](https://en.wikipedia.org/wiki/Dependency_injection)
3. Spring Boot
4. Spring Data
5. Spring Security
6. IDE
   * [Антон Архипов — Эффективная работа с IDE(A)](https://www.youtube.com/watch?v=_rj7dx6c5R8)

