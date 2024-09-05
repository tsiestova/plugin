

--якщо в Jira немає 'sqsp' [github](https://github.com/theghostco/ghost/tree/main/assets/) ghost
- hulo-dev
- github_5779LER

Якщо в Jira є 'sqsp' - [github](https://github.com/teamHulo/sqspthemes/tree/main/assets) sqspthemes
team@hulo.dev
github_5779LER

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
в [Custom CSS](./custom.css) не весь less, а лише :root{} та стилі де використовуються ці змінні, перед цим
[форматуємо](https://www.cssportal.com/css-formatter/) та [мініфікуємо](https://www.toptal.com/developers/cssminifier)  

формуємо [гугл.док](./google.doc.txt)
ще один [приклад](https://docs.google.com/document/d/1MAMlTs1WrFsj3fd9u_ayNYLjBfvdx_p0VQB358zwNcQ/edit)


Plugins
[Blog item with pagination image](https://marigold-decagon-mhdg.squarespace.com/)
https://github.com/teamHulo/sqspthemes/tree/main/assets/blog-pagination-with-image-1234

[Search](https://ukulele-brass-lldd.squarespace.com/)
https://github.com/theghostco/ghost/tree/main/assets/search-bar-1234





