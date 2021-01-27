# Внесение изменений в документы

> Принимаются корректировки опечаток

- Зарегистрируйтесь на [GitHub](https://github.com/) (если вы еще этого не сделали).

- Откройте в браузере документ, в который собираетесь внести изменения (например [этот](https://github.com/TinkoffCreditSystems/career/blob/main/interview.md))

- Нажмите кнопку редактирования ![кнопку редактирования](http://s.csssr.ru/U2Y7B7QMD/chrome_2021-01-27_11-37-34.png)

- В открышемся редакторе внесите изменения в файл. Вы всегда можете переключиться между режимом редактирования и предпросмотра кнопками `Edit File` и `Preview Changes`

> Для написания документов используется облегченный язык разметки [Markdown](https://ru.wikipedia.org/wiki/Markdown). Если Вы с ним не знакомы, ознакомьтесь со специальным [руководством](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

- Создайте новую [ветку](https://github.com/TinkoffCreditSystems/career/blob/main/CONTRIBUTING.md#ветки), дайте ей название и отправьте [изменения](https://github.com/TinkoffCreditSystems/career/blob/main/CONTRIBUTING.md#коммиты):

![](http://s.csssr.ru/U2Y7B7QMD/chrome_2021-01-27_12-00-37.png)

- На открывшейся странице нажмите `Create pull request`, после чего создастся запрос на изменение. В рамках запроса будет проведена автоматическая [проверка](https://github.com/TinkoffCreditSystems/career/blob/main/CONTRIBUTING.md#markdown-style) корректности получившейся разметки и доступности всех ссылок. После [подтверждения](https://github.com/TinkoffCreditSystems/career/blob/main/CONTRIBUTING.md#подтверждение) запроса [изменения](https://github.com/TinkoffCreditSystems/career/blob/main/CONTRIBUTING.md#релиз-изменений) попадут в основную ветку и будут доступны всем.

## Оформление зарпосов на изменение

### Ветки

Ветки желательно создавать от `main`, в названии ветки укажите файл, в который вносятся изменения.

### Коммиты

В описании к коммиту желательно указать краткое резюме о вносимых изменениях.

## Markdown Style

Все документы проверяются на существование всех присутствующих ссылок при помощи [markdown-link-check](https://github.com/tcort/markdown-link-check). Проверка происходит при создании Pull Request'а в ветку main, информация о ходе проверки и о её результатах выводится на странице Pull Request'a

### Если проверка не прошла

Необходимо проверить все ссылки в изменяемом документе, если хотя бы одна ведёт на несуществующий сайт, проверка не выполнится.

## Подтверждение

Чтобы изменения вступили в силу, их должен проверить и одобрить [Игорь Маслов](https://github.com/MaslovIgor) или [Юлия Царева](https://github.com/YuliaTsareva).

## Релиз изменений

Происходит автоматически после подтверждения изменений и их попадания в ветку `main`
