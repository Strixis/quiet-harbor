# simple config template for pug/sass/js

Набор настроек для работы с pug/sass/js.

### Набор:
1. @babel/core
2. @babel/preset-env
3. babel-loader
4. css-loader
5. css-minimizer-webpack-plugin
6. postcss
7. postcss-loader
8. postcss-preset-env
9. pug
10. pug-plugin
11. sass
12. sass-loader
13. terser-webpack-plugin
14. webpack
15. webpack-cli
16. webpack-dev-server

### Установка вручную:
1. Установка пакетов `npm i -D webpack webpack-cli webpack-dev-server terser-webpack-plugin babel-loader @babel/core @babel/preset-env css-loader css-minimizer-webpack-plugin sass sass-loader postcss postcss-loader postcss-preset-env pug pug-plugin`
2. Настройка webpack: [webpack.config.js](./webpack.config.js)
3. Поддержка браузеров: [.browserslistrc](./.browserslistrc)
4. Настройка Babel: [babel.config.json](./babel.config.json)
5. Настройка Postcss: [postcss.config.js](./postcss.config.js)
6. В package.json в раздел scripts добавляем
```
"dev": "webpack serve --mode development",
"build": "webpack --mode production"
```

*Я не буду здесь расписывать что и как настраивается. Для этого есть офф сайты, документации и статьи.*

### Быстрая установка:
1. Забираем package.json, package-lock.json, .browserslistrc, babel.config.json, postcss.config.js и webpack.config.js.
2. Устанавливаем зависимости(`npm i`).
3. ***Меняем в package.json и package-lock.json все, что считаем необходимым(name, version, description, author, license, etc.)***
