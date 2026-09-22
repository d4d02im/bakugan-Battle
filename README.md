# Bakugan Rules — Telegram Mini App / PWA

## Быстрый запуск
1. Разместите содержимое этой папки на HTTPS-хостинге.
2. Откройте `index.html` по HTTPS.
3. Для PWA браузер предложит установку или её можно выполнить через меню браузера.
4. Для Telegram Mini App привяжите URL страницы к Telegram-боту через BotFather / Web App кнопку или menu button.

## Файлы
- `index.html` — приложение
- `manifest.webmanifest` — PWA
- `sw.js` — офлайн-кэш
- `icon.svg` — иконка

Telegram WebApp SDK подключается из официального URL и автоматически активируется только при открытии внутри Telegram.
