# gulp-html-css-js-boilerplate

Шаблон для проекта.

Установка: скопируйте проект, после чего в папке проекта выполните команду

`npm i`

Структура проекта:

```
| build/
  |-- css/
  |-- fonts/
  |-- img/
  |-- js/
  |-- index.html

| node_modules/

| source/
  |-- fonts/
  |-- img/
    |-- sprite/
  |-- js/
    |-- polyfills/
  |-- sprite/
  |-- sass/
    |-- blocks/
      |-- visually-hidden.scss
    |-- fonts.scss
    |-- global.scss
    |-- mixins.scss
    |-- style.scss
    |-- variables.scss
  |-- index.html

| .babelrc
| .editorconfig
| .eslintignore
| .eslintrc.yml
| .gitignore
| .stylelintrc
| gulpfile.babel.js
| package.json
```

Режим разработки запускается командой

`npm start`

Режим релиза включает в себя оптимизацию графики и запускается командой

`npm run build`
