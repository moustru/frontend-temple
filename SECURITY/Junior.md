# Junior

#### [Вернуться](../SECURITY.md)

### Знание основных уязвимостей:

- [**XSS (межсайтовый скриптинг)**](https://wiki.rookee.ru/cross-site-scripting/?ysclid=lst9885q0493477580)

### Умение применять базовые методы защиты от уязвимостей:

- **Экранирование “небезопасных” данных таких как: пользовательский ввод строк, query strings и dynamic params в HTTP запросах, использование библиотек для облегчения работы с экранированием данных:**
  - **_Защита от XSS атак -_** [https://imvk.net/bezopasnost/kurs-po-veb-khakingu/zashchita-ot-xss-atak?ysclid=lst99kel34704173546](https://imvk.net/bezopasnost/kurs-po-veb-khakingu/zashchita-ot-xss-atak?ysclid=lst99kel34704173546)
  - **_Не пытайтесь обезопасить ввод. Экранируйте вывод -_** [https://habr.com/ru/companies/otus/articles/712830/](https://habr.com/ru/companies/otus/articles/712830/)
- **Знание “подкапотных” способов реализации защиты в используемом фреймворке/библиотеке (пример: почему в React небезопасно использовать dangerouslySetInnerHTML):**
  - **_Три типовых ошибки в сфере безопасности, о которых должен знать каждый React-разработчик -_** [https://habr.com/ru/companies/ruvds/articles/467255/](https://habr.com/ru/companies/ruvds/articles/467255/)
  - **_Опасность использования v-html в приложениях Vue -_** [https://webdevblog.ru/opasnost-ispolzovaniya-v-html-v-prilozheniyah-vue/?ysclid=lst9cfec6s24403691](https://webdevblog.ru/opasnost-ispolzovaniya-v-html-v-prilozheniyah-vue/?ysclid=lst9cfec6s24403691)

### Знание базовых методов аутентификации, авторизации и управления сессиями:

- [**Базовое использование Cookies (HttpOnly, время жизни)**](https://developer.mozilla.org/ru/docs/Web/HTTP/Cookies)
- [**Понимание различия HTTP/HTTPS**](https://selectel.ru/blog/http-https/)
- [**Токены в клиентских запросах (JWT)**](https://habr.com/ru/articles/533868/)
- [**Базовые способы разграничения доступов (role)**](https://ru.wikipedia.org/wiki/%D0%A3%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%BE%D0%BC_%D0%BD%D0%B0_%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5_%D1%80%D0%BE%D0%BB%D0%B5%D0%B9)
