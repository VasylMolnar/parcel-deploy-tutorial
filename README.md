# parcel-deploy-tutorial

## Майстерня: деплой білда від Parcel на GitHub Pages

1. Редагуємо скрипт build та додаємо `--public-url /імя_репозиторія/`
2. Редагуємо в package.json полі `"homepage": "https://ваше_имя.github.io/імя_репозиторія"`
3. Встановлюємо пакет [`npm install gh-pages`](https://www.npmjs.com/package/gh-pages)
4. Додаємо npm-скрипти
   1. `"deploy": "gh-pages -d dist"`
   2. `"predeploy": "npm run build"`
