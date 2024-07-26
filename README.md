**Задание Developer Tools**

В папке "Developer Tools" хранятся снимки экрана сайта с кнопками "Link#1", "Link#2, ... , "Link#6". Был дан сайт http://oleg.software-testing.by/test_answers_wo.php на котором было необходимо найти скрытые ссылки и получить ответы сервера, переходя по ним. В процессе выполнения задания была включена кнопка с 5ой ссылкой и с 6ой ссылкой.
**Переходя по ним, браузер получал от сервера различные ответы:**
1) 301 Moved Permanently: Запрашиваемый ресурс был перемещен на новый постоянный URL. Браузер автоматически перенаправляется на новый URL.
2) 302 Found: Запрашиваемый ресурс временно находится по другому URL. Браузер также перенаправляется, но это временное перенаправление.
3) 200 OK: Запрос был успешным, и сервер вернул запрашиваемый ресурс.
4) 500 Internal Server Error: Внутренняя ошибка сервера. Сервер столкнулся с непредвиденной ситуацией, которая помешала ему выполнить запрос.
5) 401 Unauthorized: Для доступа к запрашиваемому ресурсу требуется аутентификация. Пользователь должен предоставить корректные учетные данные.
6) 403 Forbidden: Доступ к запрашиваемому ресурсу запрещен. Даже при наличии корректных учетных данных доступ невозможен.
   
**При выполнении задания также было необходимо ответить на вопросы:**

_1. Вы тестируете какое-то web-приложение и у вас есть права доступа ко всему, что только возможно. В процессе тестирования вы заходите на какую-то страницу, а браузер вам говорит “404, страница не найдена”. Опишите свои действия._
-  Если я столкнусь с подобной проблемой, я буду выполнять следующие действия:
1) Проверю корректность URL
2) Проверю маршрутизацию
3) Проверю работу сервера
4) Посмотрю логи сервера
5) Применю инструменты разработчика
6) Проверю права доступа
7) Очищу кэш браузера
8) Проверю конфигурацию сервера
9) Свяжусь с командой разработчиков

_2. Вы тестируете какое-то web-приложение. В процессе тестирования какой-то функции сервер возвращает ошибку 403. Опишите свои действия._
- В случае возникновения подобной ошибки я:
1) Проверю права доступа
2) Проверю аутентификацию
3) Проверю коонфигурацию сервера
4) Посмотрю логи сервера
5) Применю инструменты разработчика
6) Проверю маршрутизацию
7) Проверю политику безопасности
8) Свяжусь с командой разработчиков

**Задание HTML и CSS**

В папке "HTML и CSS" хранятся HTML страницы сайта. Сайт был написан, исходя из следующих требований:

_Описание задания_
1)	_Заголовки 1го уровня для наименований страниц_
2)	_Подзаголовки 3его уровня_
3)	_Шрифт – стандартный_
4)	_Наименование страницы в браузере – “БГУИР - <Заголовок страницы>”_
5)	_1ая страница – только таблица с заголовками_
6)	_2ая страница – детализирование предмета_
7)	_По клику на ссылочку в таблице «Расписание» происходит открытие страницы «Курс лекций» с перемещением курсора на выбранный предмет_

Первая страница содержит расписание занятий, при нажатии на учебные предметы открывается вторая страница - курс лекций, на выбранном пользователем предмете.

**Задание REST**

Согласно заданию, необходимо залогиниться на https://reqres.in/ и выполнить 5 любых действий.
Действия были выполнены в POSTMAN и SOAP UI, снимки экрана и ответы сервера представлены в папке REST.

Вот список действий:

1) _Залогиниться:_
   
  Создадим POST-запрос на https://reqres.in/api/login.
  В теле запроса передадим JSON с полями "email" и "password".
  Проверим код ответа сервера (должен быть 200) и наличие токена в теле ответа.
  
3) _Получить список пользователей:_

  Создадим GET-запрос на https://reqres.in/api/users.
  Проверим код ответа сервера (должен быть 200) и наличие списка пользователей в теле ответа.
  
4) _Получить информацию о конкретном пользователе:_

  Создадим GET-запрос на https://reqres.in/api/users/1 (или другой ID пользователя).
  Проверим код ответа сервера (должен быть 200) и наличие информации о пользователе в теле ответа.
  
5) _Создать нового пользователя:_
   
  Создадим POST-запрос на https://reqres.in/api/users.
  В теле запроса передадим JSON с данными нового пользователя (например, "name", "job").
  Проверим код ответа сервера (должен быть 201) и наличие созданного пользователя в теле ответа.
  
7) _Обновить информацию о пользователе:_
   
  Создадим PUT-запрос на https://reqres.in/api/users/1 (или другой ID пользователя).
  В теле запроса передадим JSON с обновленными данными пользователя.
  Проверим код ответа сервера (должен быть 200) и наличие обновленной информации о пользователе в теле ответа.
  
**Задание SOAP**

В SOAP UI необходимо создать проект, разобраться с test-suite и запустить mock сервер.
Все шаги в виде картинок хранятся в папке SOAP.

1. _Импорт проекта_:
   - Открыть SOAP UI.
   - В меню выбрать "File" > "Import Project". (см. шаг 1)
   - Указать путь к файлу `sample-service.wsdl`. (см. шаг 2)

2. _Создание test-suite_:
   - В левой панели выбрать свой проект.
   - Правой кнопкой мыши кликнуть на проекте и выбрать "New TestSuite". (см. шаг 3)
   - Дать ему имя "Sample Service Test Suite". (см. шаг 4)

3. _Разбор элементов меню_:
   - Внутри тест-сьюта создать новый тест-кейс (правой кнопкой на тест-сьюте > "Add Test Case").
   - Внутри тест-кейса добавить новый тест-шаг (правой кнопкой на тест-кейсе > "Add Step").
   - Это меню позволяет добавлять различные типы шагов, такие как запросы, проверки, скрипты и т. д.

4. _Поднятие мок-сервера_:
   - Перейди в меню "Project" > "New SOAP MockService". (см. шаг 5 - 6)
   - Создать новый мок-сервис, указав порт и настройки.
   - Запустить мок-сервер. (см. шаг 7 - 8)
