# Igor Treyner — AI Product Manager

Готовый пакет для GitHub + Railway.

## Что внутри
- `index.html` — главная страница
- `preview.png` — Open Graph preview
- `favicon-32.png`, `favicon-192.png`, `favicon-512.png`, `favicon.ico` — иконки сайта
- `package.json` — чтобы Railway точно поднял статический сайт через `serve`
- `.gitignore`

## Локальная проверка
Если установлен Node.js:

```bash
npm install
npm run dev
```

Сайт откроется на `http://localhost:3000`.

## Загрузка на GitHub
1. Создай новый репозиторий на GitHub.
2. Залей содержимое этой папки в корень репозитория.
3. Убедись, что файл называется `index.html`.

## Деплой на Railway
1. В Railway нажми **New Project**.
2. Выбери **Deploy from GitHub repo**.
3. Подключи репозиторий.
4. Railway установит зависимости из `package.json` и запустит сайт.
5. После успешного деплоя открой **Settings → Networking**.
6. Нажми **Generate Domain** и укажи порт `3000`, если Railway спросит target port.

## Что проверить перед публикацией
- mobile: 390px
- tablet: 768px
- laptop: 1024px
- desktop: 1440px
- wide: 1920px
