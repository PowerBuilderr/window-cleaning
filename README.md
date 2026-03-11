# КристаллЧист — Мойка окон

Лендинг для услуги профессиональной мойки окон.

## Стек

- Чистый HTML / CSS / JS — один файл `index.html`
- Шрифты: Google Fonts (Montserrat, Lora)
- Форма: [Formspree](https://formspree.io)

## Структура

- **Шапка** — название, подзаголовок, две кнопки
- **Преимущества** — три карточки с иконками
- **Форма** — поля «Имя» и «Телефон», отправка через Formspree

## Настройка формы

В файле `index.html` найдите строку:

```html
<form id="contactForm" action="https://formspree.io/f/твой-тестовый-id" method="POST">
```

Замените `твой-тестовый-id` на реальный ID с сайта [formspree.io](https://formspree.io).

## Публикация на GitHub Pages

1. Создайте репозиторий на [github.com](https://github.com)
2. Загрузите `index.html`
3. Перейдите в **Settings → Pages**
4. В разделе **Branch** выберите `main` и нажмите **Save**
5. Сайт будет доступен по адресу `https://ваш-ник.github.io/название-репозитория`
