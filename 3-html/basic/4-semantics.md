# Семантические обертки

На странице **должны** быть обозначены основные смысловые секции:

- `<header>` для вводной части, повторяющейся на других страницах.
- `<main>` для главного содержимого страницы.
- `<nav>` для главной навигации по сайту.
- `<footer>` для закрывающей, дополнительной информации о странице.

Семантические обертки **могут** быть обёрнуты или вложены в другие элементы и **могут** быть стилизованы (но не использованы только для стилизации).

### Правильно

```html
<body>
  <header>
    Лого
    <nav>
      Меню
    </nav>
  </header>
  <main>
    Страница
  </main>
  <footer>
    Контакты
  </footer>
</body>
```

### Неправильно

```html
<body>
  <div>
    Лого
    <div>
      Меню
    </div>
  </div>
  <div>
    Страница
  </div>
  <div>
    Контакты
  </div>
</body>
```