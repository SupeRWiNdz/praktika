**Задание Developer Tools**

В папке "Developer Tools" хранятся снимки экрана сайта с кнопками "Link#1", "Link#2, ... , "Link#6". В процессе выполнения задания была включена кнопка с 5ой ссылкой и с 6ой ссылкой.
**Переходя по ним, браузер получал от сервера различные ответы:**
1) 301 Moved Permanently: Запрашиваемый ресурс был перемещен на новый постоянный URL. Браузер автоматически перенаправляется на новый URL.
2) 302 Found: Запрашиваемый ресурс временно находится по другому URL. Браузер также перенаправляется, но это временное перенаправление.
3) 200 OK: Запрос был успешным, и сервер вернул запрашиваемый ресурс.
4) 500 Internal Server Error: Внутренняя ошибка сервера. Сервер столкнулся с непредвиденной ситуацией, которая помешала ему выполнить запрос.
5) 401 Unauthorized: Для доступа к запрашиваемому ресурсу требуется аутентификация. Пользователь должен предоставить корректные учетные данные.
6) 403 Forbidden: Доступ к запрашиваемому ресурсу запрещен. Даже при наличии корректных учетных данных доступ невозможен.
**При выполнении задания также было необходимо ответить на вопросы:**

_1. Вы тестируете какое-то web-приложение и у вас есть права доступа ко всему, что только возможно. В процессе тестирования вы заходите на какую-то страницу, а браузер вам говорит “404, страница не найдена”. Опишите свои действия.___
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
