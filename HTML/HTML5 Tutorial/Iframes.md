# Iframes
Ифреймы используются для отображения вебстраницы на другой вебстранице.

## Синтаксис
Ифреймы определяются с помощью тега `<iframe>`:
```html
<iframe src="URL"></iframe> 
```
В атрибуте `src` указывается ссылка на вебстраницу.

## Height и Width
Для задания размеров ифрейма можно использовать как атрибуты `width` и `height`, так и CSS свойства.

## Таргет для ссылки
Iframe можно использовать как таргет для ссылки (вебстраница откроется в ифрейме). Для этого необходимо задать атрибут `target` для ссылки и атрибут `<name>` для ифрейма:
```html
<iframe src="demo_iframe.htm" name="iframe_a"></iframe>

<p><a href="https://www.w3schools.com" target="iframe_a">W3Schools.com</a></p> 
```

## Упражнения(4)
1. [Упр.1](https://codepen.io/Learde/pen/ZoXNMN)
2. [Упр.2](https://codepen.io/Learde/pen/odGRaz)
3. [Упр.3](https://codepen.io/Learde/pen/wjrbYj)
4. [Упр.4](https://codepen.io/Learde/pen/ZoXNqN)
