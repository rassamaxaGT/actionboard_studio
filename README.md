# ActionBoard Studio — Web Distribution

Официальный скомпилированный Web-релиз панели администратора и аниматора светодиодов **ActionBoard Studio**.

Данный репозиторий содержит исключительно оптимизированные скомпилированные веб-артефакты (HTML5 / CanvasKit / WebAssembly / WebHID) без исходного кода приложения.

## Деплой на Vercel

Репозиторий настроен на мгновенный **Zero-Config деплой**:
1. Перейдите на [vercel.com/new](https://vercel.com/new).
2. Выберите данный репозиторий `rassamaxaGT/actionboard_studio`.
3. Оставьте настройки сборки по умолчанию (Framework: **Other**, Build Command: **пусто**, Output Directory: **`./`**).
4. Нажмите **Deploy**.

Проект разворачивается как статический SPA-сайт с поддержкой SPA-роутинга и кеширования через `vercel.json`.
