# Секция по дизайну проектов тестирования производительности

Разбираем вопросы, связанные с планированием проектов тестирования производительности, обсуждаем различные подходы на примере определённой архитектуры.
Предложим спроектировать проект по набору входных требований. Поговорим про мониторинг, инструменты управления инфраструктурой, необходимую документацию и анализ производительности систем.

## Материалы для подготовки

### Книги:

- [Systems Performance 2nd Edition](https://www.amazon.com/Systems-Performance-Brendan-Gregg/dp/0136820158/ref=as_li_ss_tl?ie=UTF8&linkCode=sl1&tag=deirdrestraug-20&linkId=815ef3388ba65b674f4f8fd582713f24&language=en_US) / Brendan D. Gregg
- [The Art of Application Performance Testing, 2nd Edition](https://www.oreilly.com/library/view/the-art-of/9781491900536/) / Ian Molyneaux
- [Глоссарий терминов тестирования RSTQB](https://www.rstqb.org/ru/istqb-downloads.html?file=files/content/rstqb/downloads/ISTQB%20Downloads/ISTQB%20Глоссарий%20Терминов%20Тестирования%202.3.pdf) / RSTQB

### Github:

- [Qa Load Telegram Community](https://qaload.github.io/)
- [Awesome Gatling Github Page](https://github.com/aliesbelik/awesome-gatling)
- [Awesome k6 Github Page](https://github.com/grafana/awesome-k6)

### Блоги:

- [Brendan Gregg's Blog](https://www.brendangregg.com/overview.html)
- [Denis Bakhvalov's Blog](https://easyperf.net/notes/)

### Доклады:

- [Наши космические пути](https://www.youtube.com/watch?v=xxv83JfyuAg&ab_channel=IT%27sTinkoff) / Ахальцев Иоанн (Tinkoff.ru) [RU]
- [Как сделать простое НТ, если никогда его не делал?](https://dump-ekb.ru/kak-sdelat-prostoe-nt-esli-nikogda-ego-ne-delal) / Максим Рогожников (Tinkoff.ru) [RU]
- [Нагружаем банки](https://www.youtube.com/watch?v=129pEryyHQY&t=3s&ab_channel=Heisenbug) / Максим Рогожников (Tinkoff.ru) и Смирнов Вячеслав (ВТБ) [RU]
- [Воркшоп (часть 1). Встраивание в CI тестирования производительности](https://youtu.be/2wWiud1A7BM) / Сергей Чепкасов (Tinkoff.ru) [RU]
- [Воркшоп (часть 2). Встраивание в CI тестирования производительности](https://youtu.be/vbM7lRXLFD8) / Максим Рогожников (Tinkoff.ru) [RU]
- [Честное перформанс-тестирование](https://youtu.be/8Mzs3arFGZo) / Дмитрий Пивоваров (ZeroTurnaround) [RU]
- [Сложности performance-тестирования](https://youtu.be/am94iI2assY) / Андрей Акиньшин (JetBrains) [RU]
- [Анализируем перформанс с пользой для себя и окружающих](https://youtu.be/jZ0quqA1Fn8) / Андрей Акиньшин (JetBrains) [RU]
- [Учимся анализировать результаты нагрузочного тестирования](https://youtu.be/gws7L3EaeC0) / Алексей Лавренюк [RU]
- [Performance testing of microservices in action](https://youtu.be/c1xu7W7bqKc) / Alexander Kachur, Ukraine [RU]

### Статьи

- [Введение в Gatling](https://habr.com/ru/company/tinkoff/blog/655341/) 
- [Использование Gatling. Разбираемся в тестировании HTTP](https://habr.com/ru/company/tinkoff/blog/658479/)
- [Использование Gatling. Разбираемся в тестировании JDBC](https://habr.com/ru/company/tinkoff/blog/663718/) 
- [Использование Gatling. Разбираемся в тестировании gRPC](https://habr.com/ru/company/tinkoff/blog/664674/) 
- [Использование Gatling. Разбираемся в тестировании kafka](https://habr.com/ru/company/tinkoff/blog/666886/) 
- [Использование Gatling. Разбираемся в тестировании AMQP](https://habr.com/ru/company/tinkoff/blog/670768/) 
- [Анализ результатов нагрузочного тестирования](https://habr.com/ru/company/tinkoff/blog/514314/)
