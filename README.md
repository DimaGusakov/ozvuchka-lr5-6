# Озвучка ЛР 5–6

Статическая страница: `index.html`, `data.js` (главы и текст), `audio/LR5.mp3`, `audio/LR6.mp3`. Сборка не нужна.

## Бесплатный деплой (любой вариант)

**Netlify Drop, без аккаунта GitHub, проще всего**
1. Открыть https://app.netlify.com/drop и войти (бесплатно).
2. Перетащить папку `ozvuchka-site` целиком в окно.
3. Через пару секунд будет ссылка вида `https://<имя>.netlify.app`.

**GitHub Pages**
1. Создать публичный репозиторий и загрузить в него содержимое папки (Add file → Upload files).
2. Settings → Pages → Source: «Deploy from a branch», ветка `main`, папка `/ (root)`.
3. Ссылка: `https://<логин>.github.io/<репозиторий>/`.

**Cloudflare Pages**
Workers & Pages → Create → Pages → «Upload assets» → перетащить папку.

Страница будет доступна всем, у кого есть ссылка.

## Локально
`python -m http.server 8000` в этой папке, затем http://localhost:8000
