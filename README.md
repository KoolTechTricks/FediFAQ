# FediFAQ

Перевод и адаптация [FediTips] на русский язык.

Сайт создан на [Hugo] и использует тему [Hugo Book].

[FediTips]: https://fedi.tips
[Hugo]: https://gohugo.io
[Hugo Book]: https://themes.gohugo.io/themes/hugo-book

## Внести свой вклад

Вы можете [создать отчёт], если хотите сообщить о проблеме или предложить
улучшения.

Мы будем рады, если сможете напрямую внести правки или написать страницы. В
таком случае вам нужно [сделать форк репозитория], внести правки и предложить
принять изменения ([Pull Request]).

Не знаете, что можно сделать для этого проекта? Посмотрите [открытые отчёты].
Посетите [FediTips], переведите какую-нибудь страницу оттуда.

[создать отчёт]: https://github.com/KoolTechTricks/FediFAQ/issues/new
[сделать форк репозитория]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo
[Pull Request]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork
[открытые отчёты]: https://github.com/KoolTechTricks/FediFAQ/issues

## Локальный запуск

Запустите сайт локально на вашем компьютере, чтобы проверить свои правки.

Для начала вам понадобится установить следующее программное обеспечение:

- [Git](https://git-scm.com/downloads)
- [Hugo](https://gohugo.io/installation) v0.134.0 или выше

Далее используйте эти команды:

```sh
git clone --recursive https://github.com/KoolTechTricks/FediFAQ
cd FediFAQ
hugo server -D -O  # -O, чтобы открыть в браузере
```

## Лицензия

FediFAQ основан на содержимом [FediTips]. Лицензия: [CC BY-SA 4.0]

Тема [Hugo Book] доступна по лицензии MIT.

[CC BY-SA 4.0]: https://creativecommons.org/licenses/by-sa/4.0
