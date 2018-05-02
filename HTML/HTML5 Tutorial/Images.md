# Картинки
## Синтаксис
Картинки определяются в теге `<img>`. Этот тег пустой, т.е. содержит только атрибуты, без закрывающего тега. В атрибут `src` записывается ссылка на изображение, которое должно отображаться:
```html
<img src="url"> 
```

## Атрибут alt
Атрибут `alt` содержит текст, которые будет отображаться вместо картинки, если та, по той или иной причине, не загрузилась:
```html
<img src="img_chania.jpg" alt="Flowers in Chania"> 
```

> Note: Атрибут alt необходим. Без него веб-страница не будет корректно проверяться.

## Размеры изображения - Width и Height
Размеры изображения можно указать в атрибуте `style`:
```html
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;"> 
```

Альтернативный вариант - указать атрибуты `width` и `height`:
```html
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600"> 
```
Эти атрибуты содержат значение в пикселях.

> Note: Всегда указывайте ширину и высоту изображения. Если ширина и высота не указаны, страница может мерцать во время загрузки изображения.

Использовать можно оба варианта, но надежнее вариант с атрибутом `style`. Значение этого атрибута не может изменить таблица стилей.

## Картинки в другой папке/сервере
Преимущественно картинки помещают в специальную папку(например: images). Указываем путь, с учётом перехода в папку images:
```html
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;"> 
```

Можно указать ссылку на изображение с любого сервера мира. Пример:
```html
<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com"> 
```

## Анимированные изображения
HTML поддерживает GIF изображения. Указываются абсолютно таким же образом, что и обычные картинки.

## Карты
Если нужно сделать карту изображения, то используем тег `<map>`. Этот тег содержит интерактивные области картинки.

Пример:
```html
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map> 
```

Атрибут `name` тега `<map>` ассоциируется с атрибутом `usemap` тега `<img>`, создавая связь между ними.

## Фоновое изображения
Для указания фонового изображения используется параметр вида: `background-image:url(something.jpg)`

## Элемент `<picture>`
Элемент `<picture>` используется для того, чтобы повысить гибкость, при указании ресурсов изображения.

Элемент хранит несколько элементов `<source>`, каждый из которых ссылается на разные источники изображений. Таким образом, браузер может выбрать изображение, которое наилучшим образом соответствует текущему разрешению экрана / устройству.

Пример:
```html
<picture>
  <source media="(min-width: 650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width: 465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
</picture> 
```

> Note: Всегда указывайте элемент <img> в качестве последнего дочернего элемента элемента <picture>. Элемент <img> используется браузерами, которые не поддерживают элемент <picture>, или если ни один из тегов <source> не был сопоставлен.
  
## Упражнения(6)
1.[Упр.1](https://codepen.io/Learde/pen/ELXVWE)
2.[Упр.2](https://codepen.io/Learde/pen/YLQyZg)
3.[Упр.3](https://codepen.io/Learde/pen/jxwbmV)
4.[Упр.4](https://codepen.io/Learde/pen/vjZNmM)
5.[Упр.5](https://codepen.io/Learde/pen/zjzvzW)
6.[Упр.6](https://codepen.io/Learde/pen/vjZNZw)
