# Цвета
HTML-цвета указываются с использованием предопределенных имен цветов или значений: RGB, HEX, HSL, RGBA, HSLA.

## Имена цветов
HTML поддерживает [140 стандартных цветов](https://www.w3schools.com/colors/colors_names.asp), которые доступные по определённым именам.

## Цвет фона
Можно установить цвет фона элемента:
```html
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p> 
```

## Цвет текста
Можно установить цвет текста элемента:
```html
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p> 
```

## Цвет рамки
Можно установить цвет рамки элемента:
```html
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1> 
```

## RGB
Цвета можно задавать с помощью RGB значения, используя формулу:

***rgb(red, green, blue)***

Каждый из трёх параметров определяет интенсивность цвета от 0 до 255.
Несколько примеров:
* rgb(255,0,0) - красный цвет
* rgb(0,0,0) - чёрный цвет
* rgb(255,255,255) - белый цвет

Для задания серого цвета необходимо указывать три одинаковые числа в каждый из параметров.

## HEX
В HTML цвет может быть указан с использованием шестнадцатеричного значения в форме:

***#rrggbb***

Где rr(red), gg(green), bb(blue) - шестнадцатеричные значения между 00 и ff (тоже самое, что от 0 до 255).
Самое большое значение - ff, самое маленькое - 00.

Для задания серого цвета необходимо указывать три одинаковых значения.

## HSL
Задаётся в форме:

***hsl(оттенок, насыщенность, яркость)***

Оттенок задаётся значением от 0 до 360. Красный - 0, зелёный - 120, синий - 240.<br>
Насыщенность задаётся в процентном значении, где 0% - оттенок серого(цвета не видно), а 100% - полный цвет. 50% - это половина серого, но цвет всё ещё виден.<br>
Яркость цвета задаёт то, насколько ярким должен быть цвет. 0% - чёрный цвет, а 100% - белый. Оптимальный вариант - это 50%.

Для задания серого необходимо указать первые два параметра на 0 и изменять значение последнего (0% чёрный, 100% белый)

## RGBA
RGBA аналогичнен RGB, но есть дополнительный параметр, определяющий прозрачность цвета:

***rgba(red, green, blue, alpha)***

Прозрачность - это параметр, который задаётся от 0.0(полностью прозрачный) до 1.0(полностью видимый цвет)

## HSLA
HSLA аналогичен HSL, но есть дополнительный параметр, определяющий прозрачность цвета:

***hsla(hue, saturation, lightness, alpha)***

Прозрачность - это параметр, который задаётся от 0.0(полностью прозрачный) до 1.0(полностью видимый цвет)



