

--Заходимо на [github](https://github.com/theghostco/ghost/tree/main/assets/)
- hulo-dev
- github_5779LER

---створюємо папку /blog-pagination-with-image-1234/ (назва папки з карточки в джирі+4 рандомні цифри)
--- в цій папці створюємо файли:

- [back.js](./back.js.txt) - весь код з Code Injection Footer and Code Injection Header
- [full.less](./full.less.txt) - весь LESS який є в Custom CSS
- [full.js](./full.js.txt) - лишаємо пустий

- [index.js](./index.js.txt) - мініфікований JS - [мініфікатор](https://www.toptal.com/developers/javascript-minifier) 
    мініфікуємо все шо в (function(path, collection){})();

- [style.css](./style.css.txt) - ВЕСЬ Less [перетворений](https://jsonformatter.org/less-to-css) в CSS і [мініфікований](https://www.toptal.com/developers/cssminifier) 

 -- після цього всього на сайті:
 
вставти в [Code Injection Header](./header-code-inj.txt)
в [Code Injection Footer](./footer-code-inj.txt)
в [Custom CSS](./custom.css) не весь less, а лише :root{} та стилі лише де використовуються ці змінні, 
[форматуємо](https://www.cssportal.com/css-formatter/) та [мініфікуємо](https://www.toptal.com/developers/cssminifier)  
