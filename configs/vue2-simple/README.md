# simple config template for html/sass/vue

Набор настроек для работы с html/sass/vue.

### Набор:
1. @babel/core
2. @babel/preset-env
3. babel-loader
4. css-loader
5. css-minimizer-webpack-plugin
6. html-webpack-plugin
7. mini-css-extract-plugin
8. postcss
9. postcss-loader
10. postcss-preset-env
11. resolve-url-loader
12. sass
13. sass-loader
14. style-loader
15. terser-webpack-plugin
16. webpack
17. webpack-cli
18. webpack-dev-server
19. clean-webpack-plugin
20. vue
21. vue-loader
22. vue-template-compiler

### Установка вручную:
1. Установка пакетов:
* `npm i -D webpack webpack-cli webpack-dev-server terser-webpack-plugin html-webpack-plugin babel-loader @babel/core @babel/preset-env css-loader css-minimizer-webpack-plugin mini-css-extract-plugin style-loader sass sass-loader postcss postcss-loader postcss-preset-env resolve-url-loader clean-webpack-plugin vue-loader vue-template-compiler`
* `npm i vue`
2. Настройка webpack: [webpack.config.js](./webpack.config.js)
3. Поддержка браузеров: [.browserlistrc](./.browserlistrc)
4. Настройка Babel: [babel.config.json](./babel.config.json)
5. Настройка Postcss: [postcc.config.js](./postcc.config.js)
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
