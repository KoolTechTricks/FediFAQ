# Внести свой вклад

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

## Структура репозитория

- `/archetypes` — шаблоны страниц при их создании через терминал (см. [Создание страниц](#создание-страниц))
- `/content` — содержимое страниц в формате Markdown
    - `/content/assets` — изображения
- `/layouts` — шаблоны HTML при сборке сайта (см. [документацию темы Hugo Book](https://github.com/alex-shpak/hugo-book#partials))

## Создание страниц

После того как [сайт запущен локально](README.md#локальный-запуск), вы можете
создавать новые страницы через терминал:

```sh
hugo new content section/page.md
```

Это сгенерирует страницу со следующим содержимым:

```yaml
title: Page
weight: 0
draft: true
```

Замените `title` на заголовок страницы (отображается в названии вкладки
браузера) и `weight` на порядок в левой колонке раздела. Если страница готова к
публикации, уберите строку `draft`. Ниже после `---` пишите содержимое в формате
[Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Если вы хотите создать новый раздел, используйте эту команду:

```sh
hugo new content section/_index.md
```

## Стиль

- Используйте программы/расширения для проверки орфографии. Можно использовать
[LanguageTool](https://kooltechtricks.org/wiki/languagetool).

- Соблюдайте ширину строки в 80 символов.

## Изображения

Изображения хранятся в папке `/content/assets`.

```md
![Описание изображения](/assets/image.png)
```
