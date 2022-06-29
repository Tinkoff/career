# Секция по Web платформе

## Как проходит секция
В рамках секции идет обсуждение различных аспектов Web платформы и фреймворков. Также на секции проверяем знание JavaScript.

На собеседованиях мы стараемся не задавать абстрактных теоретических вопросов. Вместо этого мы предлагаем решить несколько практических задач. Для лайвкодинга мы будем использовать сервис https://codeinterview.io/ — online-IDE с возможностью запуска кода в онлайне. Шаринг экрана не потребуется.

Продолжительность секции — 90 минут.

## Этапы секции
Собеседование состоит из двух частей:

1. [Общие вопросы по Web платформе и JavaScript](#javascript)
2. Вопросы по фреймворку, на котором специализируется кандидат. В Тинькофф используются два основных стека:
   1. [Angular](#angular)
   2. [React](#react)
   
В конце собеседования у тебя будет время, чтобы пообщаться с интервьюером и задать свои вопросы. Фидбек по секции, как правило, предоставляется уже после собеседования через рекрутера.

## Материалы для подготовки

### Javascript

1. [Современный учебник JavaScript](https://learn.javascript.ru/). Состоит из трех больших частей:
   1. Язык JavaScript.
   1. Браузер: документ, события, интерфейсы.
   1. Тематические разделы. Содержат важные темы, например, про сетевые запросы и хранение данных в браузере.
2. [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS). Серия книг про deep diving в JS.
3. [Asynchronous JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous)

### Angular

В рамках обсуждения Angular часть задач будет посвящена знанию RxJS.

1. [Официальная документация](https://angular.io/docs)
2. Change Detection:
   - [NgZone](https://angular.io/guide/zone)
   - [Все, что вам нужно знать об обнаружении изменений в Angular](https://habr.com/ru/post/327004/)
   - [Faster Angular Applications](https://blog.mgechev.com/2017/11/11/faster-angular-applications-onpush-change-detection-immutable-part-1/)
3. Dependency Injection:
   - [Dependency injection in Angular](https://angular.io/guide/dependency-injection)
   - [Что можно положить в механизм Dependency Injection в Angular?](https://habr.com/ru/company/tinkoff/blog/516622/)
   - [Возможности Angular DI, о которых почти ничего не сказано в документации](https://habr.com/ru/company/tinkoff/blog/523160/)
   - [Используем DI в Angular по максимуму — концепция частных провайдеров](https://habr.com/ru/company/tinkoff/blog/507906/)
   - [Глобальные объекты в Angular](https://habr.com/ru/company/tinkoff/blog/548510/)
4. RxJS:
   - [Learn RxJS](https://www.learnrxjs.io/)
   - [RxJS Subjects](https://aalexeev239.github.io/rxjs-subjects/)
   - [Strongbrew: Примеры решения практических задач](https://blog.strongbrew.io/tag/RxJS/)
   - [Hot vs Cold Obsevables](https://benlesh.medium.com/hot-vs-cold-observables-f8094ed53339#.8x9uam5rg)

### React

1. [Официальная документация](https://reactjs.org/docs/getting-started.html)
1. [React as a UI Runtime](https://overreacted.io/react-as-a-ui-runtime/)
1. [Index as a key is an anti-pattern](https://medium.com/@robinpokorny/index-as-a-key-is-an-anti-pattern-e0349aece318)
1. [React Fiber Architecture](https://github.com/acdlite/react-fiber-architecture) - здесь неплохо написано про reconciliation в целом, часть про детали реализации (fiber) опциональна.
1. [React events in depth w/ Kent C. Dodds, Ben Alpert, & Dan Abramov](https://www.youtube.com/watch?v=dRo_egw7tBc)
1. [Getting to know React DOM's event handling system inside out](https://medium.com/the-guild/getting-to-know-react-doms-event-handling-system-inside-out-378c44d2a5d0)
1. [Новый контекст React в деталях](https://blog.csssr.ru/2018/04/06/new-react-context)
