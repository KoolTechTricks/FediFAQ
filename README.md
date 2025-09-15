# FediFAQ

Перевод и адаптация [FediTips] на русский язык.

Сайт создан на [Hugo] и использует тему [Hugo Book].

[FediTips]: https://fedi.tips
[Hugo]: https://gohugo.io
[Hugo Book]: https://themes.gohugo.io/themes/hugo-book

## Внести свой вклад

Вы можете внести свой вклад, чтобы ускорить развитие этого ресурса. Смотрите
файл [CONTRIBUTING](CONTRIBUTING.md) для подробной информации.

## Локальный запуск

Запустите сайт локально на вашем компьютере, чтобы проверить свои правки.

Для начала вам понадобится установить следующие программы:

- [Git](https://git-scm.com/downloads)
- [Hugo](https://gohugo.io/installation) последней версии (минимум v0.150.0)

Далее используйте эти команды:

```sh
git clone --recursive https://github.com/KoolTechTricks/FediFAQ
cd FediFAQ
hugo server -D -O  # -O, чтобы открыть в браузере
```

Когда сервер Hugo запущен, вы можете открыть страницу `http://localhost:1313` в
браузере. Содержимое будет обновляться автоматически по мере редактирования.

## Лицензия

Содержимое FediFAQ основано на [FediTips]. Лицензия: [CC BY-SA 4.0].

Сайт построен на теме [Hugo Book]. Лицензия: MIT.

На сайте используются значки [Material Icons] от Google. Лицензия: [Apache v2.0].

[CC BY-SA 4.0]: https://creativecommons.org/licenses/by-sa/4.0
[Material Icons]: https://fonts.google.com/icons
[Apache v2.0]: https://www.apache.org/licenses/LICENSE-2.0.html
