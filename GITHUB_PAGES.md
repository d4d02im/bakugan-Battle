# Bakugan Rules — публикация через GitHub Pages

1. На GitHub создай новый **Public repository**. Например: `bakugan-rules`.
2. Загрузи в корень репозитория **все файлы из этого архива**, включая скрытый файл `.nojekyll`.
3. Открой: **Settings → Pages**.
4. В разделе **Build and deployment** выбери:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Сохрани настройки.
6. Через некоторое время GitHub выдаст HTTPS-адрес вида:
   `https://ТВОЙ_ЛОГИН.github.io/ИМЯ_РЕПОЗИТОРИЯ/`

Этот адрес можно использовать как URL веб-приложения для Telegram Mini App.

## Важно
- Не переименовывай `index.html`.
- `manifest.webmanifest`, `sw.js` и `icon.svg` должны лежать рядом с `index.html`.
- После изменения файлов GitHub Pages обновит сайт после нового commit.
- Service Worker использует версию `v3`, чтобы браузеры не застревали на старой кэшированной версии.
