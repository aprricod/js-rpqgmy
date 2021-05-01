# Задание 9

## Какой-то заголовок

Курс по изучению react.js

Пример списка:

1. HTML
1. CSS
1. JS

### Ещё какой-то заголовок
Ниже пример *вставки кода*

```
menuBtn.addEventListener('click', function () {
    menu.classList.toggle("active")
});
```
### Полезные ссылки
[Тут](https://metanit.com/web/react/) полезная ссылка.


> тут цитата

Заголовок таблицы 1 | Заголовок таблицы 2
--------------------|-
строка 1            | строка 1
--------------------|-
строка 2            | строка 2

![тут кот в сумке](./kiven.jpg)

### Диаграмма запуска react приложения

```plantuml
@startuml
[/src] --> [/static/js/main.chunk.js]
[/node_modules] --> [/static/js/vendors~main.chunk.js]
[/public/favicon.ico] --> [/favicon.ico]
[/public/manifest.json] --> [/manifest.json]
[/manifest.json] --> [index.html]
[/public/index.html] --> [index.html]
[/favicon.ico] --> [index.html]
[/static/js/main.chunk.js] --> [index.html]
[/static/js/vendors~main.chunk.js] --> [index.html]
[/bundle.js] -l-> [index.html]
@enduml
```


# js-rpqgmy

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/js-rpqgmy)