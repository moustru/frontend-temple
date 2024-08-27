# Middle

### Умение проводить аудит производительности, выявлять узкие места и предлагать их решения:

- [**Понимание для чего нужен Lighthouse и как интерпретировать полученный результат для оптимизации приложения**](https://www.notion.so/Level-2-87c4c91bb49742f0b8b1cc8f4a53dd20?pvs=21)
- **Метрики юзабилити. знание допустимых задержек при различных действиях пользователя: на загрузке странице, при вводе текста, загрузке контента, в каких случаях нужен loader:**
    - ***10 основных юзабилити-метрик -*** [https://habr.com/ru/articles/745002/](https://habr.com/ru/articles/745002/)
- [**Симуляция медленной сети и медленных девайсов через DevTools.**](https://dandkim.com/simulate-slow-networks/test%20slow%20network%20connections/)
- **Опыт практического применения DevTools Performance для нахождения узких мест:**
    - ***Анализ производительности с помощью Chrome DevTools -*** [https://habr.com/ru/articles/715856/](https://habr.com/ru/articles/715856/)
- ***Оптимизация вычислений: уменьшение сложности алгоритма, знание способов оптимизации выполнения кода:***
    - ***13 советов, как сделать код на JavaScript качественнее и быстрее -*** [https://education.yandex.ru/journal/13-sovetov-kak-sdelat-kod-na-javascript-kachestvennee-i-bystree](https://education.yandex.ru/journal/13-sovetov-kak-sdelat-kod-na-javascript-kachestvennee-i-bystree)
    - ***Четыре способа оптимизации ПО (Python/Rust) -*** [https://habr.com/ru/companies/ruvds/articles/775868/](https://habr.com/ru/companies/ruvds/articles/775868/)
- **Применение кеширования для оптимизации выполнения js кода. Выбор способа хранения данных для оптимизации производительности:**
    - ***Кэширование кода для JavaScript-разработчиков на примере Chrome -*** [https://tproger.ru/translations/javascript-code-caching-for-devs?ysclid=lst6r0khlo159976182](https://tproger.ru/translations/javascript-code-caching-for-devs?ysclid=lst6r0khlo159976182)
- **Опыт отладки и написания оптимизированного рендеринга:**
    - ***профайлинг производительности рендеринга и нахождение бутылочных горлышек производительности:***
        - *Профилирование производительности React-приложений -* [https://habr.com/ru/companies/ruvds/articles/497988/](https://habr.com/ru/companies/ruvds/articles/497988/)
    - ***опыт оптимизации рендеринга:***
        - *Оптимизация производительности фронтенда -* [https://habr.com/ru/companies/oleg-bunin/articles/345498/](https://habr.com/ru/companies/oleg-bunin/articles/345498/)
    - ***мемоизация: особенности применения useMemo, useCallback, memo, useRef для избегания перерендера:***
        - *Повторный рендеринг и мемоизация в React -* [https://nuancesprog.ru/p/14850/?ysclid=lst71t9jmo511003091](https://nuancesprog.ru/p/14850/?ysclid=lst71t9jmo511003091)
        - *Разбираемся с мемоизацией в JavaScript -* [https://www.cat-in-web.ru/js-memoization/?ysclid=lst72m8qd9563376116](https://www.cat-in-web.ru/js-memoization/?ysclid=lst72m8qd9563376116)
        - *Что такое мемоизация? Как и когда использовать мемоизацию в JavaScript и React -* [https://habr.com/ru/articles/666522/](https://habr.com/ru/articles/666522/)
    - ***оптимизация рендеринга при изменения контекста:***
        - *React: полное руководство по повторному рендерингу -* [https://habr.com/ru/companies/timeweb/articles/684718/](https://habr.com/ru/companies/timeweb/articles/684718/)
    - ***батчинг изменения состояния:***
        - *React 18: что нужно знать о новой версии -* [https://habr.com/ru/articles/577168/](https://habr.com/ru/articles/577168/)
    - ***понимание процесса перерендера в браузере: перерасчет лейаута, стилей при изменении DOM:***
        - *Как браузер рисует страницы -* [https://doka.guide/js/how-the-browser-creates-pages/?ysclid=lst7cqteb166762106](https://doka.guide/js/how-the-browser-creates-pages/?ysclid=lst7cqteb166762106)
    - ***оптимальная реализация анимаций: css animation, requestAnimationFrame, transform:***
        - *Анимация в браузерах и как с ней работать -* [https://habr.com/ru/companies/vk/articles/794160/](https://habr.com/ru/companies/vk/articles/794160/)
- **Опыт нахождения утечек памяти через DevTools Memory:**
    - ***выявление и устранение утечек памяти и ухудшения производительности:***
        - *Проблемы поиска утечки памяти в веб-приложении с помощью Chrome DevTools -* [https://habr.com/ru/articles/236447/](https://habr.com/ru/articles/236447/)
        - *Помощь! Моя память утекает -* [https://questu.ru/articles/114892/?ysclid=lst7ezlrk8452900210](https://questu.ru/articles/114892/?ysclid=lst7ezlrk8452900210)
    - ***профайлинг, использование Heap Profiler:***
        - *Using Heap Profiler -* [https://nodejs.org/en/learn/diagnostics/memory/using-heap-profiler](https://nodejs.org/en/learn/diagnostics/memory/using-heap-profiler)

### Знание и применение передовых методов кэширования, компрессии, асинхронной загрузки ресурсов и ленивой загрузки:

- **Кеширование в js (знание и практика):**
    - [***ответов от сервера***](https://developer.mozilla.org/ru/docs/Web/HTTP/Caching)
    - [***промежуточных данных при вычислениях (мемоизация, кеширование промежуточных данных во время тяжелых вычислений):***](Level%201%20b92a636b99b44cb3895d85355c235db5.md)
        - *Кэширование и производительность веб-приложений -* [https://habr.com/ru/companies/ruvds/articles/350310/](https://habr.com/ru/companies/ruvds/articles/350310/)
        - *Кэш в JavaScript: не все Map'ы одинаково полезны -* [https://habr.com/ru/companies/tensor/articles/737432/](https://habr.com/ru/companies/tensor/articles/737432/)
- **Браузерное кеширование: загрузка скриптов из кеша, кеширование GET запросов в HTTP:**
    - ***Совершенствование производительности приложений через кэширование и CDN -*** [https://habr.com/ru/companies/otus/articles/767118/](https://habr.com/ru/companies/otus/articles/767118/)
    - ***Кэширование в браузерах и CDN -*** [https://searchengines.guru/ru/articles/44640](https://searchengines.guru/ru/articles/44640)
- **Понимание способов оптимизации размера загружаемых скриптов:**
    - ***Руководство по оптимизации JavaScript файлов -*** [https://www.dev-notes.ru/articles/javascript/optimizing-javascript-files/?ysclid=lst7qp3bng221245088](https://www.dev-notes.ru/articles/javascript/optimizing-javascript-files/?ysclid=lst7qp3bng221245088)
    - ***Как оптимизировать размер бандла SPA и ускорить загрузку приложения в несколько раз -*** [https://habr.com/ru/articles/595307/](https://habr.com/ru/articles/595307/)
- [**Анализ бандла**](https://www.notion.so/Level-1-11815b84e03846b2b57e6bd76668469d?pvs=21)
- [**Поиск и удаление неиспользуемых зависимостей**](https://stackoverflow.com/questions/21417014/npm-command-to-uninstall-or-prune-unused-packages-in-node-js)
- **Ленивая загрузка:**
    - ***Устройство ленивой загрузки в популярных фронтенд-фреймворках -*** [https://habr.com/ru/companies/vk/articles/506752/](https://habr.com/ru/companies/vk/articles/506752/)
    - ***Динамические импорты -*** [https://learn.javascript.ru/modules-dynamic-imports?ysclid=lst7y2j634830201770](https://learn.javascript.ru/modules-dynamic-imports?ysclid=lst7y2j634830201770)
    - ***Code-Splitting in React -*** [https://ru.react.js.org/docs/code-splitting.html](https://ru.react.js.org/docs/code-splitting.html)
    - ***Code Splitting in Webpack -*** [https://webpack.js.org/guides/code-splitting/#dynamic-imports](https://webpack.js.org/guides/code-splitting/#dynamic-imports)
    - ***Подгрузка контента при прокрутке -*** [https://doka.guide/js/infinite-scroll/?ysclid=lst7zrttvu176695814](https://doka.guide/js/infinite-scroll/?ysclid=lst7zrttvu176695814)
    - ***<Suspense> -*** [https://react.dev/reference/react/Suspense](https://react.dev/reference/react/Suspense)
- [**Управление загрузкой ресурсов через атрибуты тегов script и link: async, defer**](https://www.notion.so/Level-1-f07a939ab5244ab9bd85663807cfd2d5?pvs=21)