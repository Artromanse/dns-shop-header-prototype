# DNS Header — Shop Prototype

Статический HTML-прототип desktop header DNS из Figma.

Исходный макет: [Figma node `5084:9448`](https://www.figma.com/design/YDIvSOiea2rbtWednYGpDn/%F0%9F%94%B4-%D0%9C%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D1%8B---Shop---Master?node-id=5084-9448&m=dev), компонент `Header`.

## Просмотр

Локально открыть `index.html` в браузере.

Если в системе установлен Python, можно проверить через локальный сервер:

```bash
python -m http.server 8080
```

Затем открыть `http://localhost:8080`.

## Состав

- `index.html` — прототип header на чистом HTML/CSS/JS.
- `assets/` — локально сохранённые ассеты из Figma.
- `404.html` — статическая fallback-страница для GitHub Pages.

## Реализовано

- Desktop layout с max-width 1380px и отступами под 1920px viewport.
- Top row: язык, город, навигационные ссылки, телефон.
- Bottom row: DNS logo/catalog block, search field, compare/wishlist/cart/profile actions.
- Hover/active состояния для интерактивных элементов и focus ring для поиска.
- Горизонтальная прокрутка на узких экранах, чтобы сохранить pixel-close desktop-композицию.
