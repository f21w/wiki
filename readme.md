# База знаний play2go.cloud

Расположена по адресу [wiki.play2go.cloud](https://wiki.play2go.cloud)

## Запуск

```sh
npm i
npm dev
```

## Сборка

```sh
npm build
```

## Написание своих статей

Статьи можно писать в [Visual Studio Code](https://code.visualstudio.com/) либо же в [Obsidian](https://obsidian.md/). Допустимо использование других редакторов, поддерживающих Markdown разметку.

[Документация VitePress](https://vitepress.dev) <br>
Сайдбар генерируется автоматически, статьи вручную добавлять туда нет нужды.

Markdown файлы должны проходить проверку линтером [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint), а также все предложения не должны содержать каких-либо пунктуационных и грамматических ошибок (буква **Ё** тоже считается, но её преднамеренная/непреднамеренная замена на **Е** не возбраняется и в случае чего текст может быть впоследствии [ёфицирован](https://ru.wikipedia.org/wiki/Ёфикатор) любым коллаборатором)
