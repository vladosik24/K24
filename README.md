# K24 Digital Studio

Статичний сайт: HTML5 + CSS3 + vanilla JS, без збірки та залежностей.

## Запуск
Відкрийте `index.html` у браузері. Для локального сервера: `python -m http.server` у цій папці.

## Публікація
Завантажте всю папку на GitHub Pages, Netlify, Vercel або будь-який хостинг статичних сайтів.

## Структура
- `index.html` — розмітка та SEO (title, description, Open Graph)
- `styles.css` — стилі, змінні кольорів у `:root`
- `script.js` — мобільне меню, поява елементів, підтримка prefers-reduced-motion
- `assets/` — `favicon.svg`, `logo.svg`, `images/`

## Редагування
- Кольори: змінні `--bg`, `--gold` тощо на початку `styles.css`
- Портфоліо: блоки `.work` у `index.html`; оновлюйте статуси проєктів, коли вони зміняться
- Контакти: посилання Telegram, YouTube, Twitch у секції `#contacts`
- Шрифти (Cormorant Garamond, Manrope) підвантажуються з Google Fonts; без інтернету працюють системні запасні
