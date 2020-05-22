# Mesto

Место - это сервис, где люди могут делиться фотографиями своих любимых мест.

[Mesto на GH-Pages](https://varyalikhanina.github.io/mesto)

## Используемые технологии
HTML, CSS, JS, API, Webpack, BEM

## Установка
Перед началом работы проверьте наличие установленного node.js и npm

Склонируйте репозиторий
```bash
git clone https://github.com/varyalikhanina/mesto.git
```

Установите зависимости:
```bash
npm install
```

Для разработки используйте команду
```bash
npm run dev
```

Для сборки используйте команду
```bash
npm run build
```
Для публикации на GH-Pages
```bash
npm deploy
```

## Использование
При клике на Edit открывается попап, который можно заполнить своими данными (имя и род деятельности). Поля формы валидируются.
Кнопка в правом верхнем углу страницы - для добавления карточки с вашим любимым местом. Поля формы также валидируются.
При наведении на карточку появляется кнопка для удаления. Также здесь есть возможность поставить лайк.
При нажатии на карточку открывается попап с соответствующей фотографией.