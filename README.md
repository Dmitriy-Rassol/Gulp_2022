Сборщик проектов Gulp 2022

## Установка пакетов NPM
```js
npm install
```

## Список пакетов

- browser-sync
-	del
-	gulp
-	gulp-autoprefixer
-	gulp-clean-css
-	gulp-file-include
-	gulp-fonter
-	gulp-group-css-media-queries
-	gulp-if
-	gulp-imagemin
-	gulp-newer
-	gulp-notify
-	gulp-plumber
-	gulp-pug
-	gulp-rename
-	gulp-replace
-	gulp-sass
-	gulp-svg-sprite
-	gulp-ttf2woff2
-	gulp-util
-	gulp-version-number
-	gulp-webp
-	gulp-webp-html-nosvg
-	gulp-webpcss
-	gulp-zip
-	sass
-	swiper
-	vinyl-ftp
-	webp-converter
-	webpack
-	webpack-stream

## Сценарии NPM

Cобираем проект в режиме разработчика
```js
npm run dev
```
---
Собираем проект 
```js
npm run build
```
---
Создаем архив проекта 
```
npm run zip
```
---
Заливаем проект на сервер, все настройки в файле gulp/config/ftp.js 
```
npm run deploy
```
---
Создаем спрайт из иконок
```
npm run svgSprive
```
---
Настройки VSCode для изображений
-открыть VSCode
-настройки
-палитра команд
-вводим >Open Settings (JSON)
-в файле прописываем строчки
```
 "path-autocomplete.pathMappings": {
        "@img": "${folder}/src/img",
        "@scss": "${folder}/src/scss",
        "@js": "${folder}/src/js",
    }
```
