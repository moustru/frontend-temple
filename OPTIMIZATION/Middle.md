# Middle

#### [На главную](../OPTIMIZATION.md)

### Умение проводить аудит производительности, выявлять узкие места и предлагать их решения:

- [**Понимание для чего нужен Lighthouse и как интерпретировать полученный результат для оптимизации приложения**](https://www.notion.so/Level-2-87c4c91bb49742f0b8b1cc8f4a53dd20?pvs=21)
- **Метрики юзабилити. знание допустимых задержек при различных действиях пользователя: на загрузке странице, при вводе текста, загрузке контента, в каких случаях нужен loader:**
  - **_10 основных юзабилити-метрик -_** [https://habr.com/ru/articles/745002/](https://habr.com/ru/articles/745002/)
- [**Симуляция медленной сети и медленных девайсов через DevTools.**](https://dandkim.com/simulate-slow-networks/test%20slow%20network%20connections/)
- **Опыт практического применения DevTools Performance для нахождения узких мест:**
  - **_Анализ производительности с помощью Chrome DevTools -_** [https://habr.com/ru/articles/715856/](https://habr.com/ru/articles/715856/)
- **_Оптимизация вычислений: уменьшение сложности алгоритма, знание способов оптимизации выполнения кода:_**
  - **_13 советов, как сделать код на JavaScript качественнее и быстрее -_** [https://education.yandex.ru/journal/13-sovetov-kak-sdelat-kod-na-javascript-kachestvennee-i-bystree](https://education.yandex.ru/journal/13-sovetov-kak-sdelat-kod-na-javascript-kachestvennee-i-bystree)
  - **_Четыре способа оптимизации ПО (Python/Rust) -_** [https://habr.com/ru/companies/ruvds/articles/775868/](https://habr.com/ru/companies/ruvds/articles/775868/)
- **Применение кеширования для оптимизации выполнения js кода. Выбор способа хранения данных для оптимизации производительности:**
  - **_Кэширование кода для JavaScript-разработчиков на примере Chrome -_** [https://tproger.ru/translations/javascript-code-caching-for-devs?ysclid=lst6r0khlo159976182](https://tproger.ru/translations/javascript-code-caching-for-devs?ysclid=lst6r0khlo159976182)
- **Опыт отладки и написания оптимизированного рендеринга:**
  - **_профайлинг производительности рендеринга и нахождение бутылочных горлышек производительности:_**
    - _Профилирование производительности React-приложений -_ [https://habr.com/ru/companies/ruvds/articles/497988/](https://habr.com/ru/companies/ruvds/articles/497988/)
  - **_опыт оптимизации рендеринга:_**
    - _Оптимизация производительности фронтенда -_ [https://habr.com/ru/companies/oleg-bunin/articles/345498/](https://habr.com/ru/companies/oleg-bunin/articles/345498/)
  - **_мемоизация: особенности применения useMemo, useCallback, memo, useRef для избегания перерендера:_**
    - _Повторный рендеринг и мемоизация в React -_ [https://nuancesprog.ru/p/14850/?ysclid=lst71t9jmo511003091](https://nuancesprog.ru/p/14850/?ysclid=lst71t9jmo511003091)
    - _Разбираемся с мемоизацией в JavaScript -_ [https://www.cat-in-web.ru/js-memoization/?ysclid=lst72m8qd9563376116](https://www.cat-in-web.ru/js-memoization/?ysclid=lst72m8qd9563376116)
    - _Что такое мемоизация? Как и когда использовать мемоизацию в JavaScript и React -_ [https://habr.com/ru/articles/666522/](https://habr.com/ru/articles/666522/)
  - **_оптимизация рендеринга при изменения контекста:_**
    - _React: полное руководство по повторному рендерингу -_ [https://habr.com/ru/companies/timeweb/articles/684718/](https://habr.com/ru/companies/timeweb/articles/684718/)
  - **_батчинг изменения состояния:_**
    - _React 18: что нужно знать о новой версии -_ [https://habr.com/ru/articles/577168/](https://habr.com/ru/articles/577168/)
  - **_понимание процесса перерендера в браузере: перерасчет лейаута, стилей при изменении DOM:_**
    - _Как браузер рисует страницы -_ [https://doka.guide/js/how-the-browser-creates-pages/?ysclid=lst7cqteb166762106](https://doka.guide/js/how-the-browser-creates-pages/?ysclid=lst7cqteb166762106)
  - **_оптимальная реализация анимаций: css animation, requestAnimationFrame, transform:_**
    - _Анимация в браузерах и как с ней работать -_ [https://habr.com/ru/companies/vk/articles/794160/](https://habr.com/ru/companies/vk/articles/794160/)
- **Опыт нахождения утечек памяти через DevTools Memory:**
  - **_выявление и устранение утечек памяти и ухудшения производительности:_**
    - _Проблемы поиска утечки памяти в веб-приложении с помощью Chrome DevTools -_ [https://habr.com/ru/articles/236447/](https://habr.com/ru/articles/236447/)
    - _Помощь! Моя память утекает -_ [https://questu.ru/articles/114892/?ysclid=lst7ezlrk8452900210](https://questu.ru/articles/114892/?ysclid=lst7ezlrk8452900210)
  - **_профайлинг, использование Heap Profiler:_**
    - _Using Heap Profiler -_ [https://nodejs.org/en/learn/diagnostics/memory/using-heap-profiler](https://nodejs.org/en/learn/diagnostics/memory/using-heap-profiler)

### Знание и применение передовых методов кэширования, компрессии, асинхронной загрузки ресурсов и ленивой загрузки:

- **Кеширование в js (знание и практика):**
  - [**_ответов от сервера_**](https://developer.mozilla.org/ru/docs/Web/HTTP/Caching)
  - [**_промежуточных данных при вычислениях (мемоизация, кеширование промежуточных данных во время тяжелых вычислений):_**](Level%201%20b92a636b99b44cb3895d85355c235db5.md)
    - _Кэширование и производительность веб-приложений -_ [https://habr.com/ru/companies/ruvds/articles/350310/](https://habr.com/ru/companies/ruvds/articles/350310/)
    - _Кэш в JavaScript: не все Map'ы одинаково полезны -_ [https://habr.com/ru/companies/tensor/articles/737432/](https://habr.com/ru/companies/tensor/articles/737432/)
- **Браузерное кеширование: загрузка скриптов из кеша, кеширование GET запросов в HTTP:**
  - **_Совершенствование производительности приложений через кэширование и CDN -_** [https://habr.com/ru/companies/otus/articles/767118/](https://habr.com/ru/companies/otus/articles/767118/)
  - **_Кэширование в браузерах и CDN -_** [https://searchengines.guru/ru/articles/44640](https://searchengines.guru/ru/articles/44640)
- **Понимание способов оптимизации размера загружаемых скриптов:**
  - **_Руководство по оптимизации JavaScript файлов -_** [https://www.dev-notes.ru/articles/javascript/optimizing-javascript-files/?ysclid=lst7qp3bng221245088](https://www.dev-notes.ru/articles/javascript/optimizing-javascript-files/?ysclid=lst7qp3bng221245088)
  - **_Как оптимизировать размер бандла SPA и ускорить загрузку приложения в несколько раз -_** [https://habr.com/ru/articles/595307/](https://habr.com/ru/articles/595307/)
- [**Анализ бандла**](https://www.notion.so/Level-1-11815b84e03846b2b57e6bd76668469d?pvs=21)
- [**Поиск и удаление неиспользуемых зависимостей**](https://stackoverflow.com/questions/21417014/npm-command-to-uninstall-or-prune-unused-packages-in-node-js)
- **Ленивая загрузка:**
  - **_Устройство ленивой загрузки в популярных фронтенд-фреймворках -_** [https://habr.com/ru/companies/vk/articles/506752/](https://habr.com/ru/companies/vk/articles/506752/)
  - **_Динамические импорты -_** [https://learn.javascript.ru/modules-dynamic-imports?ysclid=lst7y2j634830201770](https://learn.javascript.ru/modules-dynamic-imports?ysclid=lst7y2j634830201770)
  - **_Code-Splitting in React -_** [https://ru.react.js.org/docs/code-splitting.html](https://ru.react.js.org/docs/code-splitting.html)
  - **_Code Splitting in Webpack -_** [https://webpack.js.org/guides/code-splitting/#dynamic-imports](https://webpack.js.org/guides/code-splitting/#dynamic-imports)
  - **_Подгрузка контента при прокрутке -_** [https://doka.guide/js/infinite-scroll/?ysclid=lst7zrttvu176695814](https://doka.guide/js/infinite-scroll/?ysclid=lst7zrttvu176695814)
  - **_<Suspense> -_** [https://react.dev/reference/react/Suspense](https://react.dev/reference/react/Suspense)
- [**Управление загрузкой ресурсов через атрибуты тегов script и link: async, defer**](https://www.notion.so/Level-1-f07a939ab5244ab9bd85663807cfd2d5?pvs=21)
